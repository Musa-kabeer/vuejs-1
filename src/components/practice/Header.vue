<template>
  <h1
    :class="
      (size == 'sm' ? 'text-xs' : size == 'lg' ? 'text-xl' : 'text-base') + ' ' +
      (weight == 'med'
        ? 'font-medium'
        : weight == 'bold'
        ? 'font-bold'
        : 'font-normal')
    "
  >
    <slot />
  </h1>
</template>

<script>
export default {
  props: {
    size: String,
    weight: String,
  },
};
</script>

<style scoped></style>
