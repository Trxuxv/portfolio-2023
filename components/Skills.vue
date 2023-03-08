<!-- Please remove this file from your project -->
<template>
  <div class="w-5/6 h-screen">
    <div class="w-full text-gray-200 cursor-default">
      <p class="text-center text-purple-600 text-5xl font-bold cursor-default pt-2">
        My Skills <span @click="goHome()" class="mt-2 float-right text-base flex items-center bg-pink-800 rounded-full p-2 text-white font-light px-4 shadow-2xl cursor-pointer hover:bg-purple-800">
          Back to Home
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8 ml-2 bg-purple-800 p-2 rounded-full ">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 9l6-6m0 0l6 6m-6-6v12a6 6 0 01-12 0v-3" />
          </svg>
        </span>
      </p>
      <section>
        <div class="container max-w-5xl mx-auto m-8">
          <div class="flex flex-wrap">
            <div class="w-5/6 sm:w-1/2 p-6">
              <h3 class="text-3xl font-bold leading-none mb-3 text-gray-200">
                Front End Development
              </h3>
              <div class="text-gray-300 mb-8 text-lg font-light">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at ipsum
                eu nunc commodo posuere et sit amet ligula.
                <br />

                <div class="text-gray-200 h-20">
                  <div class="py-2 text-white text-sm font-medium">
                    Technologies:
                    <a class="text-white text-sm py-1 px-2 bg-red-600 rounded-full mx-1"
                      >Angular +2</a
                    >
                    <a class="text-white text-sm py-1 px-2 bg-red-500 rounded-full mx-1"
                      >AngularJS</a
                    >
                    <a
                      style="background-color: #57bfdc"
                      class="text-white py-1 px-2 rounded-full mx-1"
                      >ReactJS</a
                    >
                    <a
                      style="background-color: #d86500"
                      class="text-white py-1 px-2 rounded-full mx-1"
                      >HTML</a
                    >
                  </div>
                  <div class="pt-3 text-sm font-medium">
                    <a class="text-white py-1 px-2 bg-green-600 rounded-full mt-4 mx-1"
                      >CSS</a
                    >
                    <a
                      class="text-white py-1 px-2 bg-yellow-400 rounded-full mx-1 font-medium"
                      >Javascript</a
                    >
                    <a
                      style="background-color: rgb(13 108 111)"
                      class="text-white py-1 px-2 rounded-full mx-1 font-medium"
                      >TailwindCSS</a
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full sm:w-1/2 p-6">
              <img
                src="./../static/image/vectors/3.svg"
                class="w-5/6 sm:h-64 mx-auto"
                alt=""
              />
            </div>
          </div>
          <div class="flex flex-wrap flex-col-reverse sm:flex-row">
            <div class="w-full sm:w-1/2 p-6 mt-6">
              <img
                class="w-full sm:h-64 mx-auto"
                src="./../static/image/vectors/2.svg"
                alt=""
              />
            </div>
            <div class="w-full sm:w-1/2 p-6 mt-6">
              <div class="align-middle">
                <h3 class="text-3xl text-gray-200 font-bold leading-none mb-3">
                  Back End Development
                </h3>
                <div class="text-gray-300 font-light mb-8 text-lg">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at
                  ipsum eu nunc commodo posuere et sit amet ligula.
                  <br />
                  <div class="text-gray-200 h-20">
                    <div class="py-2 text-white text-lg">
                      Technologies:
                      <a
                        class="text-white text-sm py-1 px-2 bg-green-600 rounded-full mx-1"
                        >C#</a
                      >
                      <a
                        class="text-white text-sm py-1 px-2 bg-purple-500 rounded-full mx-1"
                        >.NET</a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap">
            <div class="w-5/6 sm:w-1/2 p-6">
              <h3 class="text-3xl text-gray-200 font-bold leading-none mb-3">
                Database Management
              </h3>
              <p class="text-gray-300 mb-8 text-lg font-light">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at ipsum
                eu nunc commodo posuere et sit amet ligula.
                <br />
                <br />

                Technologies:
                <a class="text-white text-sm py-1 px-2 bg-yellow-600 rounded-full mx-1"
                  >SQL Server</a
                >
                <a class="text-white text-sm py-1 px-2 bg-blue-500 rounded-full mx-1"
                  >MySQL</a
                >
              </p>
            </div>
            <div class="w-full sm:w-1/2 p-6">
              <img
                src="./../static/image/vectors/4.svg"
                class="w-5/6 sm:h-64 mx-auto"
                alt=""
              />
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "Skills",
  methods: {
    goHome() {
      document.getElementById("home-content")?.scrollIntoView();
    },
  }
};
</script>
<style scoped></style>
