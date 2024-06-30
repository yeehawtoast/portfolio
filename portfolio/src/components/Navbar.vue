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
  position: sticky;
  top: 0;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  height: 6rem;
  border-bottom: 1px solid #1a1a1a;
  background-color: rgba(40,40,40,0.95);
  backdrop-filter: blur(8px);
  box-shadow: 0 4px 4px rgba(0,0,0,0.3);
  z-index: 99999999999;
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