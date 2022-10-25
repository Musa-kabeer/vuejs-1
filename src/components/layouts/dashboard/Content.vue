<template>
  <!-- SIDE--BAR -->
  <div class="flex">
    <Aside />
    <div class="px-5 pt-4 lg:px-0 lg:flex lg:items-center lg:justify-around">
      <!-- SEARCH -->
      <div class="w-full -mb-4 flex justify-between items-center lg:hidden">
        <div class="flex items-center w-full">
          <i
            class="text-xl text-gray-300 cursor-pointer fa-solid fa-magnifying-glass"
          ></i>
          <input
            class="bg-transparent w-full outline-none mx-2 text-xl border-b-2"
            type="text"
            placeholder="Search files..."
          />
        </div>
        <div class="flex items-center justify-between w-14">
          <div class="flex">
            <i
              id="bright__Btn"
              class="text-base cursor-pointer text-gray-400 fa-solid fa-sun"
            ></i>
            <i
              id="dark__Btn"
              class="hidden text-base cursor-pointer text-gray-400 fa-solid fa-bars"
            ></i>
            <i
              id="triggerBtn"
              class="lg:hidden ml-2 text-base cursor-pointer text-gray-400 fa-solid fa-bars"
            ></i>
          </div>
          <img class="w-8 ml-2" src="/img/user.svg" alt="" />
        </div>
      </div>
      <!-- COOKIES -->
      <div
        class="w-full h-full mt-8 lg:py-0 lg:w-4/12 lg:px-6 bg-transparent lg:pl-24 lg:pr-4"
      >
        <div class="bg-yellow-100 w-full h-30 p-2 rounded-md">
          <h3 class="text-xl font-medium text-blue-900">Cookies Update</h3>
          <p class="text-sm font-medium">
            Dear parters, please refer to the update release notes for the
            updates on the cookies.
          </p>
        </div>
        <h1 class="text-gray-600 font-medium mt-2">USER INFO</h1>
        <div
          class="py-4 px-1.5 bg-transparent w-full h-30 rounded-md shadow-xl"
        >
          <div class="flex justify-between px-5 content-center w-full">
            <div class="flex">
              <i
                class="w-10 h-10 pt-1.5 pl-2 text-2xl text-blue-400 rounded-full bg-blue-100 fa-solid fa-gem"
              ></i>
              <div class="ml-5">
                <p class="text-sm font-medium text-gray-500">Your Plan</p>
                <span class="text-blue-800 font-medium">Basic Free</span>
              </div>
            </div>
            <i
              class="py-2 px-1 text-1.5xl text-gray-300 cursor-pointer fa-solid fa-circle-arrow-right"
            ></i>
          </div>
          <div class="flex justify-between px-5 content-center w-full mt-4">
            <div class="flex">
              <i
                class="w-10 h-10 pt-1 pl-3 text-2xl text-yellow-400 rounded-full bg-yellow-100 fa-solid fa-file"
              ></i>
              <div class="ml-5">
                <p class="text-sm font-medium text-gray-500">File Uploaded</p>
                <span class="text-blue-800 font-medium">28</span>
              </div>
            </div>
            <i
              class="py-2 px-1 text-1.5xl text-gray-300 cursor-pointer fa-solid fa-circle-arrow-right"
            ></i>
          </div>
        </div>
        <div class="w-full flex content-center mt-7">
          <div class="flex justify-between px-5 content-center w-full mt-4">
            <div class="flex">
              <i
                class="w-10 h-10 pt-1.5 pl-3 text-2xl text-blue-400 rounded-full bg-blue-100 fa-solid fa-dollar-sign"
              ></i>
              <div class="ml-5">
                <p class="text-sm font-medium text-gray-500">Affiliate</p>
                <span class="text-blue-800 font-medium">$23.65</span>
              </div>
            </div>
            <i
              class="py-2 px-1 text-1.5xl text-gray-300 cursor-pointer fa-solid fa-circle-arrow-right"
            ></i>
          </div>
        </div>
        <div
          class="flex justify-between content-center py-6 px-8 bg-blue-50 mt-6 w-full h-30 rounded-md"
        >
          <img class="w-12 h-12 rounded-full" src="img/progress.png" alt="" />
          <div class="flex flex-col">
            <div class="flex justify-center content-center text-sm font-medium">
              <div class="w-3 h-3 bg-blue-300 mr-3"></div>
              <p class="-mt-1 -ml-1">LEFT</p>
            </div>
            <div
              class="flex justify-center content-center text-sm mt-3.5 font-medium"
            >
              <div class="w-3 h-3 bg-blue-800"></div>
              <p class="-mt-1 ml-1">USED</p>
            </div>
          </div>
          <div>
            <p class="text-sm font-medium text-blue-800">
              10.68 <span class="text-gray-500 text-xs">Gb</span>
            </p>
            <p class="text-sm font-medium text-blue-800">
              5.32 <span class="text-gray-500 text-xs">Gb</span>
            </p>
          </div>
        </div>
        <div
          class="flex justify-between content-center py-4 px-3 bg-blue-900 mt-4 w-full h-36 rounded-md text-white"
        >
          <div class="flex flex-col justify-between">
            <div class="text-2xl font-medium lg:text-base">
              <i class="text-2xl fa-solid fa-bolt lg:text-xl"></i>&nbsp; UPGRADE
              PLAN
            </div>
            <p class="text-5xl font-medium lg:text-2xl">+50 Gb</p>
            <p class="font-medium text-2xl lg:text-xs">$14.99 &rightarrow;</p>
          </div>
          <img class="w-32 lg:w-20" src="img/rocket.svg" alt="" />
        </div>
      </div>
      <!-- introduced -->Q
      <div class="py-4 lg:w-7/12">
        <!-- SEARCH -->
        <div
          class="w-full mb-2 hidden md:hidden lg:flex justify-between items-center"
        >
          <div class="flex items-center w-full">
            <i
              class="text-xl text-gray-300 cursor-pointer fa-solid fa-magnifying-glass"
            ></i>
            <input
              class="bg-transparent w-full outline-none mx-2 text-xl border-b-2"
              type="text"
              placeholder="Search files..."
            />
          </div>
          <div class="flex items-center justify-between w-14">
            <div class="">
              <i
                id="Large__bright__Btn"
                class="text-base cursor-pointer text-gray-400 fa-solid fa-sun"
              ></i>
              <i
                id="Large__dark__Btn"
                class="hidden text-base cursor-pointer text-gray-400 fa-solid fa-bars"
              ></i>
            </div>
            <img class="w-8 ml-2" src="/img/user.svg" alt="" />
          </div>
        </div>
        <!-- NAME -->
        <div>
          <h1 class="text-2xl font-medium text-blue-900">Hello,</h1>
          <p class="text-base font-medium text-gray-500">
            Do you want to make new uploads today?
          </p>
        </div>
        <!-- FILES -->
        <div class="w-full h-30 bg-gray-100 rounded-md mt-4 p-4">
          <h2 class="text-blue-900 font-medium text-xl border-b pb-2">
            File Suggestion
          </h2>
          <div class="flex flex-wrap justify-center">
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-folder"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Voulux Design
              </p>
            </div>
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-folder"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Website Dev...
              </p>
            </div>
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-brands fa-youtube"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Youtube Tut...
              </p>
            </div>
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-file-word"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Business De...
              </p>
            </div>
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-file-pdf"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Design_bri...
              </p>
            </div>
            <div class="flex flex-col ml-4" ml-5>
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-folder"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Photos<span class="text-gray-400">.zip</span>
              </p>
            </div>
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-folder"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                272_FFSa<span class="text-gray-400">.txt</span>
              </p>
            </div>
            <div class="flex flex-col ml-4">
              <i
                class="text-gray-500 text-4xl text-center cursor-pointer mt-2 fa-solid fa-file-excel"
              ></i>
              <p class="text-xs font-medium text-blue-800 w-20 mt-1">
                Dashboard<span class="text-gray-400">.xis</span>
              </p>
            </div>
          </div>
        </div>
        <!-- RECENT -->
        <div class="flex justify-between mt-5 w-full">
          <h3 class="text-xl font-medium text-blue-900">Recent Files</h3>
          <div class="w-12 flex justify-between">
            <i
              class="text-2xl -ml-4 cursor-pointer text-gray-400 fa-solid fa-bars"
            ></i>
            <i
              class="text-2xl cursor-pointer text-gray-400 fa-solid fa-bars"
            ></i>
          </div>
        </div>
        <!-- WORKING  -->
        <div class="my-3">
          <div class="rounded-md bg-blue-100 flex justify-between px-3 py-1">
            <h2 class="text-sm font-medium">NAME</h2>
            <h2 class="text-sm font-medium">LAST EDITED</h2>
            <h2 class="text-sm font-medium">MEMBERS</h2>
          </div>
          <div
            class="flex justify-between items-center px-3 py-2 bg-gray-100 mt-3 rounded-md"
          >
            <h4 class="text-blue-900 text-xs font-medium">
              <i
                class="text-gray-500 text-center text-xs cursor-pointer fa-brands fa-youtube"
              ></i>
              Youtube Tutorial<span class="text-gray-500">.mp4</span>
            </h4>
            <p class="text-xs font-medium -ml-32">
              Today,
              <span class="text-gray-500 font-medium">7:39 PM</span>
            </p>
            <img class="rounded-full w-7 h-7" src="img/avatar2.png" alt="" />
            <p class="text-gray-300 text-medium hidden text-3xl">...</p>
          </div>
          <div
            class="flex justify-between items-center px-3 py-2 bg-gray-100 mt-3 rounded-md"
          >
            <h4 class="text-blue-900 text-xs font-medium">
              <i
                class="text-gray-500 text-center text-xs cursor-pointer mt-2 fa-brands fa-youtube"
              ></i>
              Business Description<span class="text-gray-500">.mp4</span>
            </h4>
            <p class="text-xs font-medium mr-32">
              Today,
              <span class="text-gray-500 font-medium">10:30 PM</span>
            </p>
            <img class="rounded-full w-7 h-7" src="img/avatar2.png" alt="" />
            <p class="text-gray-300 text-medium hidden text-3xl">...</p>
          </div>
          <div
            class="flex justify-between items-center px-3 py-2 bg-gray-100 mt-3 rounded-md"
          >
            <h4 class="text-blue-900 text-xs font-medium">
              <i
                class="text-gray-500 text-center text-xs cursor-pointer mt-2 fa-brands fa-youtube"
              ></i>
              Dashboard<span class="text-gray-500">.xis</span>
            </h4>
            <p class="text-xs font-medium mr-20">
              Today,
              <span class="text-gray-500 font-medium">7:39 PM</span>
            </p>
            <img class="rounded-full w-7 h-7" src="img/avatar2.png" alt="" />
            <p class="text-gray-300 text-medium hidden text-3xl">...</p>
          </div>
          <div
            class="flex justify-between items-center px-3 py-2 bg-gray-100 mt-3 rounded-md"
          >
            <h4 class="text-blue-900 text-xs font-medium">
              <i
                class="text-gray-500 text-center text-xs cursor-pointer mt-2 fa-brands fa-youtube"
              ></i>
              design_brief<span class="text-gray-500">.pdf</span>
            </h4>
            <p class="text-xs font-medium mr-24">
              Today,
              <span class="text-gray-500 font-medium">10:15 PM</span>
            </p>
            <img class="rounded-full w-7 h-7" src="img/avatar2.png" alt="" />
            <p class="text-gray-300 text-medium hidden text-3xl">...</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Aside from "./Sidebar.vue";
export default { components: { Aside } };
</script>

<style scoped></style>
