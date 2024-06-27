<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
    <div class="hero">
  <span class ="imagedot"></span>

  </div>
  <span class="text">Howdy! I'm Chris</span>
</template>

<style scoped>
.hero{
    display: flex;
    flex-direction: row;
    justify-content: center;
    margin-top: 100px;
    margin-bottom: 10px;
}
.text{
    display: flex;
    color: white;
    font-family: 'Monserrat', sans-serif;
    font-weight: bold;
    font-size: 72px;
    justify-content: center;
}
.imagedot{
    height: 200px;
    width: 200px;
    background-color: white;
    border-radius: 50%;
    display: inline-block;
    
}
</style>