<template>
  <div
    v-if="display === false"
    class="bg-slate-300 w-screen h-screen flex flex-col justify-center items-center"
  >
    <label for="">Enter username:</label>
    <input v-model="user" type="text" class="outline-none px-2" />
    <button
      @click="goBtn()"
      class="w-28 h-6 mt-2 cursor-pointer text-white fonr-medium bg-slate-500 rounded-md"
    >
      GO
    </button>
  </div>
  <div v-if="display">
    <Slider />
  </div>
</template>

<script>
import Slider from "./Sliders.vue";
export default {
  components: {
    Slider,
  },
  data() {
    return {
      user: "",
      display: false,
    };
  },
  methods: {
    goBtn() {
      if (this.user === "") {
        return;
      } else {
        this.display = true;
      }
    },
  },
};
</script>
