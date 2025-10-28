<template>
  <div>
    <TwoInOne
      :name="'Welcome To About Page'"
      :imgsrc="home"
      :visit="'/services'"
      :btnName="'Get Started'"
    />
  </div>
</template>

<script setup>
import TwoInOne from "../components/TwoInOne";
import home from "../assets/images/home.png";
</script>

<style scoped>
</style>
