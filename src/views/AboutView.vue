<template>
  <div>
    <TwoOne
      :name="'Welcome To About Page'"
      :imgsrc="home"
      :visit="'/services'"
      :btnName="'Services'"
    />
  </div>
</template>

<script setup>
import TwoOne from "../components/TwoOne.vue";
import home from "../assets/images/home.jpg";
</script>

<style scoped>
</style>
