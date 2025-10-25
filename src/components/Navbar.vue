<template>
  <div>
    <header
      class="flex justify-between items-center bg-white shadow-md h-20 px-5 lg:px-24"
    >
      <div
        class="text-3xl font-extrabold text-blue-600 hover:text-blue-700 cursor-pointer"
      >
        <router-link to="/"><i class="bi bi-code"></i> BlockGem</router-link>
      </div>
      <div class="">
        <router-link
          to="/"
          class="text-slate-500 hover:text-slate-700 text-xl font-medium"
          >Home</router-link
        >
        <router-link
          to="/about"
          class="text-slate-500 hover:text-slate-700 text-xl font-medium"
          >About</router-link
        >
        <router-link
          to="/services"
          class="text-slate-500 hover:text-slate-700 text-xl font-medium"
          >Services</router-link
        >
      </div>
    </header>
  </div>
</template>

<script setup>
</script>

<style scoped>
</style>
