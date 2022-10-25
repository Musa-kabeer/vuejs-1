<template>
  <!-- 1 NAVIGATION -->
  <div
    class="hidden transition ease-in-out w-2/12 fixed z-100 lg:w-1/12 h-screen lg:flex flex-col items-center justify-between bg-purple-900 p-4"
  >
    <i
      @click="$emit('close')"
      class="text-white text-3xl fa-sharp fa-solid fa-egg"
    ></i>
    <ul class="p-0">
      <li class="py-2">
        <i
          class="text-0.5xl mt-1 cursor-pointer text-white fa-solid fa-house"
        ></i>
      </li>

      <li class="py-2">
        <i
          class="text-0.5xl mt-1 cursor-pointer text-white fa-solid fa-bars"
        ></i>
      </li>

      <li class="py-2">
        <i
          class="text-0.5xl mt-1 cursor-pointer text-white fa-solid fa-wand-magic-sparkles"
        ></i>
      </li>

      <li class="py-2">
        <i
          class="text-0.5xl mt-1 cursor-pointer text-white fa-solid fa-pen-nib"
        ></i>
      </li>

      <li class="py-2">
        <i
          class="text-0.5xl mt-1 cursor-pointer text-white fa-solid fa-sun"
        ></i>
      </li>
    </ul>
    <div>
      <i class="text-0.5xl cursor-pointer text-white fa-solid fa-signal"></i>
      <span class="text-xs text-white">5.32/16Gb</span>
      <i
        class="text-0.5xl ml-1 cursor-pointer text-white fa-solid fa-window-maximize"
      ></i>
    </div>
  </div>
</template>

<script>
export default {};
</script>
