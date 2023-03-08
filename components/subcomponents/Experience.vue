<template>
  <div class="card-experience">
    <div class="card-experience-border-top">
    </div>
    <div class="img">
    </div>
    <span> Person</span>
    <p class="job"> Job Title</p>
    <button> Click
    </button>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Experience",
});
</script>
<style scoped>
.card-experience {
  width: 190px;
  height: 254px;
  background: #3405a3;
  border-radius: 15px;
  box-shadow: 1px 5px 60px 0px #100a886b;
 }

 .card-experience .card-experience-border-top {
  width: 60%;
  height: 3%;
  background: #6b64f3;
  margin: auto;
  border-radius: 0px 0px 15px 15px;
 }

 .card-experience span {
  font-weight: 600;
  color: white;
  text-align: center;
  display: block;
  padding-top: 10px;
  font-size: 16px;
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
  background: #6b64f3;
  border-radius: 15px;
  margin: auto;
  margin-top: 25px;
 }

 .card-experience button {
  padding: 8px 25px;
  display: block;
  margin: auto;
  border-radius: 8px;
  border: none;
  margin-top: 30px;
  background: #6b64f3;
  color: white;
  font-weight: 600;
 }

 .card-experience button:hover {
  background: #534bf3;
 }</style>
