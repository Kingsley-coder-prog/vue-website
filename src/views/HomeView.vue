<template>
  <div>
    <TwoInOne
      :name="'Grow Your Business With'"
      :imgsrc="home"
      :visit="'/about'"
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