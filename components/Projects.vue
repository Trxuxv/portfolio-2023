<template>
  <div class="w-full flex p-2 relative h-4/6 mx-auto py-4">
    <div class="w-1/3">
      <div class="w-2/6 h-4/5 absolute mt-10 ml-20 shadow-xl">
        <div class="terminal_toolbar bg-black">
          <div class="butt">
            <button class="btn bg-red-500"></button>
            <button class="btn bg-yellow-500"></button>
            <button class="btn bg-green-500"></button>
          </div>
          <p class="user">debora.maciel@dev: ~</p>
          <div class="add_tab"></div>
        </div>
        <div class="terminal_body bg-gray-900">
          <div class="terminal_promt">
            <span class="terminal_user">debora.maciel@dev:</span>
            <span class="terminal_location">~</span>
            <span class="terminal_bling">$</span>
            <!-- <input type="text"/> -->
            <span class="terminal_cursor"></span>
          </div>
        </div>
      </div>
    </div>
    <div class="main w-1/3 flex">
      <div class="card rounded-lg" id="c1">
        <div class="w-full h-full bg-purple-900 border-3 border-gray-900 p-1 rounded">
          <div class="card-image">
            <img src="./../static/image/projects/1.png" alt="" />
          </div>
          <div class="category">Illustration</div>
          <div class="heading text-gray-200 text-gray-200">
            A heading that must span over two lines
            <div class="author">By <span class="name">Abi</span> 4 days ago</div>
          </div>
        </div>
      </div>
      <div class="card rounded-lg mt-10" id="c2">
        <div class="w-full h-full bg-purple-900 border-3 border-gray-900 p-1 rounded">
          <div class="card-image">
            <img src="./../static/image/projects/3.png" alt="" />
          </div>
          <div class="category">Illustration</div>
          <div class="heading text-gray-200">
            A heading that must span over two lines
            <div class="author">By <span class="name">Abi</span> 4 days ago</div>
          </div>
        </div>
      </div>
      <div class="card rounded-lg mt-10" id="c3">
        <div class="w-full h-full bg-purple-900 border-3 border-gray-900 p-1 rounded">
          <div class="card-image">
            <img src="./../static/image/projects/2.png" alt="" />
          </div>
          <div class="category font-medium text-white">HALIX PREV</div>
          <div class="heading text-gray-200">
            A heading that must span over two lines
            <div class="author">By <span class="name">Abi</span> 4 days ago</div>
          </div>
        </div>
      </div>
      <div class="card rounded-lg mt-10" id="c4">
        <div class="w-full h-full bg-purple-900 border-3 border-gray-900 p-1 rounded">
          <div class="card-image">
            <img src="./../static/image/projects/4.png" alt="" />
          </div>
          <div class="category font-medium text-white">HALIX PREV</div>
          <div class="heading text-gray-200">
            A heading that must span over two lines
            <div class="author">By <span class="name">Abi</span> 4 days ago</div>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-10 w-1/3 flex">
      <div class="card-experience shadow-md ml-10 bg-gray-900">
        <div class="card-experience-border-top bg-pink-800"></div>
        <div class="img">
          <img class="rounded-lg w-16" src="./../static/image/company/1.jpg" alt="" />
        </div>
        <span class="text-sm"> SOFTWARE DEVELOPER PL</span>
        <p class="job">MangniFinance</p>
        <button class="text-xs w-16 bg-purple-500 h-16 text-gray-900 flex items-center justify-center rounded-full">2022 <br> moment</button>
      </div>
      <div class="card-experience shadow-md ml-8 bg-gray-900">
        <div class="card-experience-border-top bg-pink-800"></div>
        <div class="img">
          <img
            class="p-2 bg-black h-16 rounded-lg w-16"
            src="./../static/image/company/2.svg"
            alt=""
          />
        </div>
        <span class="text-sm"> SOFTWARE DEVELOPER JR</span>
        <p class="job">Techer</p>
        <button class="text-xs w-16 bg-purple-500 h-16 text-gray-900 flex items-center justify-center rounded-full">2021 <br> moment</button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Projects",
});
</script>
<style scoped>
.card {
  margin-right: -8%;
  margin-top: 2%;
  width: 190px;
  height: 254px;
  background: #d3d3d333;
  position: absolute;
  transition: 0.3s ease-in-out;
  cursor: pointer;
  box-shadow: 0px 0px 30px -10px #0000004d;
}

#c1 {
  background-color: black;
}

#c2 {
  background-color: blue;
}

#c3 {
  background-color: red;
}

#c4 {
  background-color: green;
}

.main:hover #c1 {
  transform: translateX(-100px) rotate(-40deg);
}

.main:hover #c2 {
  transform: translateX(-50px) rotate(-30deg);
}

.main:hover #c3 {
  transform: translateX(0) rotate(-20deg);
}

.main:hover #c4 {
  transform: translateX(50px) rotate(-10deg);
}

#c1:hover {
  transform: translateX(-150px) rotate(0deg) !important;
}

#c2:hover {
  transform: translateX(-100px) rotate(0deg) !important;
}

#c3:hover {
  transform: translateX(-50px) rotate(0deg) !important;
}

#c4:hover {
  transform: translateX(50px) rotate(0deg) !important;
}

.main {
  display: grid;
  place-items: center;
}

card-image {
  background-color: rgb(236, 236, 236);
  width: 100%;
  height: 60%;
  border-radius: 6px 6px 0 0;
}

.card-image:hover {
  transform: scale(0.98);
}

.category {
  text-transform: uppercase;
  font-size: 0.7em;
  padding: 10px 7px 0;
}

.category:hover {
  cursor: pointer;
}

.heading {
  font-weight: 600;
  padding: 7px;
}

.heading:hover {
  cursor: pointer;
}

.author {
  color: gray;
  font-weight: 400;
  font-size: 11px;
  padding-top: 20px;
}

.name {
  font-weight: 600;
}

.name:hover {
  cursor: pointer;
}

.terminal_toolbar {
  display: flex;
  height: 30px;
  align-items: center;
  padding: 0 8px;
  box-sizing: border-box;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
  justify-content: space-between;
}

.butt {
  display: flex;
  align-items: center;
}

.btn {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  margin-right: 5px;
  font-size: 8px;
  height: 12px;
  width: 12px;
  box-sizing: border-box;
  border: none;
  border-radius: 100%;
  text-shadow: 0px 1px 0px rgba(255, 255, 255, 0.2);
  box-shadow: 0px 0px 1px 0px #41403a, 0px 1px 1px 0px #474642;
}

.btn-color {
  background: #ee411a;
}

.btn:hover {
  cursor: pointer;
}

.btn:focus {
  outline: none;
}

.butt--exit {
  background: linear-gradient(#f37458 0%, #de4c12 100%);
}

.add_tab {
  color: #fff;
  padding: 0 6px;
  border-radius: 4px 4px 0 0;
  border-bottom: none;
  cursor: pointer;
}

.user {
  color: #d5d0ce;
  margin-left: 6px;
  font-size: 14px;
  line-height: 15px;
}

.terminal_body {
  height: calc(100% - 30px);
  padding-top: 2px;
  margin-top: -1px;
  font-size: 12px;
  border-bottom-left-radius: 5px;
  border-bottom-right-radius: 5px;
}

.terminal_promt {
  display: flex;
}

.terminal_promt span {
  margin-left: 4px;
}

.terminal_user {
  color: #1eff8e;
}

.terminal_location {
  color: #4878c0;
}

.terminal_bling {
  color: #dddddd;
}

.terminal_cursor {
  display: block;
  height: 14px;
  width: 5px;
  margin-left: 10px;
  animation: curbl 1200ms linear infinite;
}

@keyframes curbl {
  0% {
    background: #ffffff;
  }

  49% {
    background: #ffffff;
  }

  60% {
    background: transparent;
  }

  99% {
    background: transparent;
  }

  100% {
    background: #ffffff;
  }
}

.card-experience {
  width: 190px;
  height: 254px;
  border-radius: 15px;
  box-shadow: 1px 5px 60px 0px #100a886b;
}

.card-experience .card-experience-border-top {
  width: 60%;
  height: 3%;
  margin: auto;
  border-radius: 0px 0px 15px 15px;
}

.card-experience span {
  font-weight: 600;
  color: white;
  text-align: center;
  display: block;
  padding-top: 10px;
}

.card-experience .job {
  font-weight: 400;
  color: white;
  display: block;
  text-align: center;
  padding-top: 3px;
  font-size: 12px;
}

.card-experience .img {
  width: 70px;
  height: 80px;
  border-radius: 15px;
  margin: auto;
  margin-top: 25px;
}

.card-experience button {
  display: block;
  margin: auto;
  border: none;
  margin-top: 30px;
  font-weight: 600;
}
</style>
