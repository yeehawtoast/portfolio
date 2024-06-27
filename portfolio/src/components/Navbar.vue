<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="navbar">
    <button class="navbut" type="button">Home</button>
    <button class="navbut" type="button">About</button>
    <button class="navbut" type="button">Resume</button>
    <button class="navbut" type="button">Portfolio</button>
    <button class="navbut" type="button">Contact Me</button>
  </div>
</template>

<style scoped>
.navbar{
 display: flex;
 flex-direction: row;
 justify-content: space-evenly;
}
.navbut{
  background-color: #27374D;
  color: azure;
  border: 0px;
  font-size: 25px;
  font-family: "Montserrat", sans-serif;
  font-weight: bold;
}
</style>