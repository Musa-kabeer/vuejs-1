<template>
  <div class="bg-slate-300 w-screen h-screen relative">
    <div @click="toggle()" class="ml-4 absolute top-4 z-10 cursor-pointer">
      <div
        :class="
          isActive ? 'transition ease transform rotate-45 translate-y-1.5' : ''
        "
        class="w-8 h-1 bg-white mt-1"
      ></div>
      <div
        :class="isActive ? 'transition ease transform opacity-0' : ''"
        class="w-8 h-1 bg-white mt-1"
      ></div>
      <div
        :class="
          isActive
            ? 'transition ease transform -rotate-45 -translate-y-1.5'
            : ''
        "
        class="w-8 h-1 bg-white mt-1"
      ></div>
    </div>
    <div
      :class="
        isActive ? 'transition ease-in-out  translate-x-0 duration-1000' : ''
      "
      v-if="isActive === true"
      class="absolute top-0 left-0 bg-slate-800 lg:w-1/6 md:2/6 w-1/2 h-screen text-white flex justify-center items-center"
    >
      <ul class="flex justify-center items-center flex-col">
        <li class="text-4xl mt-8">Home</li>
        <li class="text-4xl mt-8">Blog</li>
        <li class="text-4xl mt-8">About</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isActive: false,
    };
  },
  methods: {
    toggle() {
      if (this.isActive === false) {
        this.isActive = true;
      } else {
        this.isActive = false;
      }
    },
  },
};
</script>

<style scoped></style>
