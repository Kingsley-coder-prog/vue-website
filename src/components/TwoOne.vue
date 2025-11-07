<template>
  <div
    class="container mx-auto px-5 lg:px-20 h-[100vh] md:h-[80vh] flex flex-col-reverse md:flex-row justify-center md:justify-between items-center gap-10"
  >
    <!-- <div class=""> -->
    <div class="w-full flex items-center flex-col md:items-start">
      <h1 class="text-2xl md:text-4xl text-slate-700 my-1">
        {{ name }} <br />
        <strong class="text-blue-700 text-5xl lg:text-6xl font-bold"
          >BlockGem Team</strong
        >
      </h1>
      <p class="text-2xl md:text-4xl text-slate-700 my-1">
        We are the team of talented developers
      </p>
      <router-link
        :to="visit"
        class="bg-blue-600 hover:bg-blue-700 outline-none px-12 py-4 rounded-full mt-3 text-white text-xl font-medium cursor-pointer"
      >
        {{ btnName }}
      </router-link>
    </div>
    <div class="home">
      <img :src="imgsrc" alt="team-img" class="w-[800px] h-[100%] mt-5" />
    </div>
    <!-- </div> -->
  </div>
</template>

<script setup>
import { RouterLink } from "vue-router";
import { defineProps } from "vue";
const props = defineProps(["name", "imgsrc", "visit", "btnName"]);
</script>

<style scoped>
.home {
  animation: up-down 1s alternate infinite;
}

@keyframes up-down {
  0% {
    transform: translateY(10px);
  }
  100% {
    transform: translateY(-10px);
  }
}
</style>