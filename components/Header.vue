<template>
  <div class="w-full h-full flex z-1 blur">
    <div class="w-2/3 h-full flex flex-col px-10 z-50">
      <div class="flex items-end h-1/6 font-medium  my-6 text-gray-200 text-lg">
        Hi, there!
      </div>
      <div class="h-1/6 text-6xl font-bold mb-10 mb-10 text-gray-200">
        <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-800 z-90"> Débora Maciel</span> is here
        <br />
        to be your developer!
      </div>
      <div class="font-normal text-gray-200 text-lg">
        I am here ready to help you <br/>
        in develop your own solution being you a person or a company
      </div>
      <div class="my-12">
        <button
          class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 py-3 px-8 rounded-full text-sm font-medium ml-4 text-black"
        >
          Let's Discover
        </button>
      </div>
    </div>
    <div class="w-2/4 h-full flex items-center justify-center">
      >
      <button class="bg-white mr-64 absolute rounded-lg shadow-xl flex">
        <p class="flex items-center ml-1 justify-center h-full mt-1">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-9 h-9 rounded-lg p-1 bg-purple-800 text-white mt-1"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M14.25 9.75L16.5 12l-2.25 2.25m-4.5 0L7.5 12l2.25-2.25M6 20.25h12A2.25 2.25 0 0020.25 18V6A2.25 2.25 0 0018 3.75H6A2.25 2.25 0 003.75 6v12A2.25 2.25 0 006 20.25z"
            />
          </svg>
        </p>
        <p class="mx-2 flex text-left flex-col text-xs p-1">
          <b class="font-bold text-base">+60</b>
          Projects
        </p>
      </button>
      <button class="bg-white ml-64 static absolute rounded-lg shadow-xl flex">
        <p class="flex items-center ml-1 justify-center h-full mt-1">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-9 h-9 rounded-lg p-1 bg-purple-800 text-white mt-1"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M14.25 9.75L16.5 12l-2.25 2.25m-4.5 0L7.5 12l2.25-2.25M6 20.25h12A2.25 2.25 0 0020.25 18V6A2.25 2.25 0 0018 3.75H6A2.25 2.25 0 003.75 6v12A2.25 2.25 0 006 20.25z"
            />
          </svg>
        </p>
        <p class="mx-2 flex text-left flex-col text-xs p-1">
          <b class="font-bold text-base">+60</b>
          Projects
        </p>
      </button>
      <div
        class="p-1 w-2/5 rounded-full"
        style="padding: 4%; border-radius: 10% 38%"
      >
        <img class="bg-gradient-to-r from-indigo-800 via-purple-600 to-pink-400 rounded-full" src="./../static/image/6.png" alt="" />
      </div>
    </div>
    <!-- <span
      class="absolute bg-pink-800 opacity-20 w-1/2 h-5/6 z-0 blur left-1 top-0"
      style="    border-radius: 50% 20% / 10% 40%;
      top: 4%;
      rotate: 12deg;"
    ></span> -->
    <!-- <span class="absolute bg-pink-800 w-10 h-10 blur rounded-full right-10"></span>
    <span
      class="absolute bg-pink-800 opacity-10 w-16 h-16 blur rounded-full right-40 top-20"
    ></span>
    <span
      class="absolute bg-pink-800 opacity-40 w-4 h-4 blur rounded-full right-40"
    ></span> -->
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>
<style>
.letsdiscover {
  box-shadow: rgba(228, 196, 17, 0.898) 0px 2px 5px 0px, #997b0e 0px 1px 1px 0px;
}
</style>
