<template>
  <div
    class="w-full h-screen flex justify-center items-center flex-col bg-red-200"
  >
    <p
      v-for="slider in sliders"
      :key="slider.id"
      class="w-32 h-14 -mt-4 rounded-md bg-red-500 text-white font-medium mb-10 flex justify-center items-center text-center relative"
    >
      <span
        @click="deleteMessage(slider.id)"
        class="absolute right-1 -top-1.5 text-white z-99 font-bold cursor-pointer"
        >X</span
      >

      {{ slider.content }}
    </p>

    <div>
      <input
        v-model="inputData"
        type="text"
        class="px-2 w-54 h-18 outline-none"
      />
      <button
        class="py-2 px-4 bg-red-500 rounded-md ml-4"
        @click="addNotification()"
      >
        Add notification
      </button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
      inputData: "",
      sliders: [],
    };
  },
  methods: {
    addNotification() {
      if (this.inputData === "") {
        return;
      } else {
        this.count++;
        this.sliders.push({
          id: this.count,
          content: this.inputData,
        });
      }

      console.log(this.sliders);
    },
    deleteMessage(id) {
      const findId = this.sliders.findIndex((obj) => {
        return obj.id === id;
      });

      this.sliders.splice(findId, 1);
    },
    messageDuration() {
      setTimeout(() => {
        this.sliders.shift();
        console.log("HELLO WORLD");
      }, 5000);
    },
  },
  created() {
    return this.messageDuration();
  },
};
</script>
