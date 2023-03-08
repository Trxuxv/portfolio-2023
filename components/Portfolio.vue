<!-- Please remove this file from your project -->
<template>
  <div
    class="w-5/6 h-screen"
  >
  <div class="w-full text-gray-200 cursor-default">
    <p class="text-center text-purple-600 text-5xl font-bold cursor-default pt-4">
      Portfolio
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
  <div>
    <div class="container">
      <div class="carousel">
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
        <div class="carousel__face"></div>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: "Portfolio",

  methods: {
    goHome(){
      document.getElementById('home-content')?.scrollIntoView();

    }}
};
</script>
<style scoped>
.container {
  position: relative;
  width: 500px;
  margin: 100px auto 0 auto;
  perspective: 1000px;
}

.carousel {
  position: absolute;
  width: 100%;
  height: 100%;
  transform-style: preserve-3d;
  animation: rotate360 60s infinite forwards linear;
}
.carousel__face {
  position: absolute;
  width: 300px;
  height: 187px;
  top: 20px;
  left: 10px;
  right: 10px;
  background-size: cover;
  box-shadow:inset 0 0 0 2000px rgba(0,0,0,0.5);
  display: flex;
}

span {
  margin: auto;
}

.carousel__face:nth-child(1) {
  background-image: url("./../static/image/projects/1.png");
  transform: rotateY(  0deg) translateZ(430px); }
.carousel__face:nth-child(2) {
  background-image: url("./../static/image/projects/2.png");
    transform: rotateY( 40deg) translateZ(430px); }
.carousel__face:nth-child(3) {
  background-image: url("./../static/image/projects/3.png");
  transform: rotateY( 80deg) translateZ(430px); }
.carousel__face:nth-child(4) {
  background-image: url("./../static/image/projects/4.png");
  transform: rotateY(120deg) translateZ(430px); }
.carousel__face:nth-child(5) {
  background-image: url("./../static/image/projects/5.png");
 transform: rotateY(160deg) translateZ(430px); }
.carousel__face:nth-child(6) {
  background-image: url("./../static/image/projects/6.png");
 transform: rotateY(200deg) translateZ(430px); }
.carousel__face:nth-child(7) {
  background-image: url("./../static/image/projects/7.png");
 transform: rotateY(240deg) translateZ(430px); }
.carousel__face:nth-child(8) {
  background-image: url("./../static/image/projects/8.png");
  transform: rotateY(280deg) translateZ(430px); }
.carousel__face:nth-child(9) {
  background-image: url("./../static/image/projects/9.png");
  transform: rotateY(320deg) translateZ(430px); }



@keyframes rotate360 {
  from {
    transform: rotateY(0deg);
  }
  to {
    transform: rotateY(-360deg);
  }
}

</style>
