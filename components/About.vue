<!-- Please remove this file from your project -->
<template>
  <div class="w-5/6 h-screen">
    <div class="w-full text-gray-200 cursor-default">
      <p class="text-center text-purple-600 text-5xl font-bold cursor-default pt-4">
        About
        <span
          @click="goHome()"
          class="mt-2 float-right text-base flex items-center bg-pink-800 rounded-full p-2 text-white font-light px-4 shadow-2xl cursor-pointer hover:bg-purple-800"
        >
          Back to Home
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-8 h-8 ml-2 bg-purple-800 p-2 rounded-full"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M9 9l6-6m0 0l6 6m-6-6v12a6 6 0 01-12 0v-3"
            />
          </svg>
        </span>
      </p>
    </div>
    <div class="w-full bg-white h-5/6 shadow-md mt-10 rounded-lg opacity-10 flex">
      <div class="w-1/2 h-full">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem
        Ipsum has been the industry's standard dummy text ever since the 1500s, when an
        unknown printer took a galley of type and scrambled it to make a type specimen
        book. It has survived not only five centuries, but also the leap into electronic
        typesetting, remaining essentially unchanged. It was popularised in the 1960s with
        the release of Letraset sheets containing Lorem Ipsum passages, and more recently
        with desktop publishing software like Aldus PageMaker including versions of Lorem
        Ipsum.
      </div>
      <div class="w-1/2 h-full">

      </div>
    </div>
    <div></div>
  </div>
</template>

<script>
export default {
  name: "About",
  methods: {
    goHome() {
      document.getElementById("home-content")?.scrollIntoView();
    },
  },
};
</script>
<style scoped>
.skills {
  height: 400px;
}
</style>
