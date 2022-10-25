<template>
  <div>
    <!-- LOGIN PAGE -->
    <div
      class="h-screen w-full bg-gradient-to-tr from-blue-400 to-red-400 flex justify-center py-12"
    >
      <div class="bg-gray-100 w-96 h-30 rounded-md shadow-2xl py-12 px-9">
        <h1 class="text-center text-3xl font-medium">LOGIN</h1>
        <div class="mt-4">
          <label class="text-sm font-semibold">Username</label> <br />
          <input
            class="bg-transparent border-b-2 w-full h-10 outline-none px-1"
            type="text"
            placeholder="Type your username"
          />
          <br />
          <label class="text-sm font-semibold">Password</label> <br />
          <input
            class="bg-transparent border-b-2 w-full h-10 outline-none px-1"
            type="password"
            placeholder="Type your password"
          />
        </div>
        <p class="text-sm text-right text-gray-400">Forget password?</p>
        <button
          class="w-full h-12 rounded-full text-xl font-medium text-white bg-gradient-to-r from-blue-300 to-red-400 mt-5"
          type="button"
        >
          <a target="_blank" href="./nextPage.html">LOGIN</a>
        </button>
        <p class="mt-5 text-center text-sm text-gray-400 font-medium">
          Or sign Up Using
        </p>
        <div class="flex items-stretch justify-center content-center mt-4">
          <i
            class="text-xl text-blue-900 self-center justify-center rounded-full cursor-pointer fa-brands fa-facebook-f"
          ></i>
          <i
            class="text-xl text-blue-400 mx-4 text-white self-center justify-center rounded-full cursor-pointer fa-brands fa-twitter"
          ></i>
          <i
            class="text-xl text-red-600 self-center justify-center rounded-full cursor-pointer fa-brands fa-google"
          ></i>
        </div>
        <p class="mt-20 text-center leading-9 text-gray-500 text-base">
          Or sign Up Using <br />
          <a class="font-medium" href="/">SIGN UP</a>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
