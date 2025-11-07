<template>
  <div class="bg-white shadow-lg sm:skew-y-6">
    <img :src="imgsrc" :alt="title" class="w-full object-cover h-[200px]" />

    <div class="text p-9">
      <h1 class="text-slate-950 py-1 font-medium text-lg">{{ title }}</h1>
      <p class="text-slate-700 py-1 font-medium text-base">{{ desc }}</p>
      <button
        class="bg-blue-600 hover:bg-blue-700 outline-none px-10 py-3 rounded-full mt-3 text-white text-lg font-medium cursor-pointer"
      >
        Go Somewhere
      </button>
    </div>
  </div>
</template>

<script setup>
const props = defineProps(["imgsrc", "title", "desc"]);
</script>

<style scoped>
</style>