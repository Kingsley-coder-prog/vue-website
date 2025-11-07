<template>
  <div>
    <TwoOne
      :name="'Grow Your Business With'"
      :imgsrc="home"
      :visit="'/about'"
      :btnName="'Get Started'"
    />
  </div>
</template>

<script setup>
import TwoOne from "../components/TwoOne.vue";
import home from "../assets/images/home.jpg";
</script>

<style scoped>
</style>