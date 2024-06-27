<script setup lang="ts">
//import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue';
</script>

<template>
  <header>
  <Navbar/>
  <Hero/>
  </header>
</template>
<style>
html{
  background-image: url('./assets/background.svg');
}
</style>