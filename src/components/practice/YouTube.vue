<template>
  <div
    class="bg-gray-800 w-screen h-screen flex flex-col justify-center items-center text-white"
  >
    <h1>NAME: {{ name }}</h1>
    <h1 v-bind="$attrs">Likes: {{ likes }}</h1>
    <h1>Likes: {{ isPublished ? "Yes" : "No" }}</h1>
  </div>
</template>

<script>
export default {
  // props: ["name"],
  props: {
    name: {
      type: String,
      default: "MUSA ADEWALE",
      required: true,
    },
    likes: Number,
    isPublished: Boolean,
  },
  components: {},
  data() {
    return {};
  },
  inheritAttrs: false,
};
</script>
