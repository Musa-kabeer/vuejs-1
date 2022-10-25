<template>
  <h2 v-for="(arr, index) in arrs" :key="arr">
    <slot :text="arr" :index="index"></slot>
  </h2>
</template>

<script>
export default {
  data() {
    return {
      arrs: ["Volvo", "Camery", "Venza"],
    };
  },
  methods: {},
};
</script>
