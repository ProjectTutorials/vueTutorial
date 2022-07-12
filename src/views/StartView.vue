<script setup>
import Header from "../components/Header.vue";
import GetStarted from "../pages/GetStarted.vue";
</script>

<template>
  <div class="about">
    <Header/>
    <GetStarted/>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
