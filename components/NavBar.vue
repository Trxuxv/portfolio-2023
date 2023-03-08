<!-- Please remove this file from your project -->
<template>
  <div
    class="w-full h-16 flex items-center text-sm font-medium text-gray-300 z-50"
  >
    <div class="z-50 w-2/4 pl-20 text-xl font-black">Débora Maciel</div>
    <div class="w-1/4 flex justify-between">
      <span class="cursor-pointer hover:text-purple-700" @click="goHome()">Home</span>
      <span class="cursor-pointer hover:text-purple-700" @click="goSkill()">Skills</span>
      <span class="cursor-pointer hover:text-purple-700" @click="goPortfolio()">Portfolio</span>
      <span class="cursor-pointer hover:text-purple-700" @click="goAbout()">About</span>
      <span class="cursor-pointer hover:text-purple-700" @click="goContact()">Contact</span>
    </div>
    <div class="w-2/4 flex justify-end pr-20">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M3.75 9h16.5m-16.5 6.75h16.5"
        />
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",

  methods: {
    goHome(){
      document.getElementById('home-content')?.scrollIntoView();

    },
    goSkill(){
      document.getElementById('skill-content')?.scrollIntoView();

    },
    goContact(){
      document.getElementById('contact-content')?.scrollIntoView();
    },

    goAbout(){
      document.getElementById('about-content')?.scrollIntoView();
    },

    goPortfolio(){
      document.getElementById('portfolio-content')?.scrollIntoView();
    }


  }
};
</script>
