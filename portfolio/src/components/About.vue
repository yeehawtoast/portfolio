<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
<div class="container">
  <span class="text">This is my About</span>
  <p>I lived somewhere else, I live here now. I worked somewhere else, I work here now.</p>
</div>

</template>

<style scoped>
.container{
  height: 100vh;
}
.text{
    display: flex;
    color: white;
    font-family: 'Monserrat', sans-serif;
    font-weight: bold;
    font-size: 72px;
    justify-content: center;
}
p{
  display: flex;
    color: white;
    font-family: 'Monserrat', sans-serif;
    font-weight: bold;
    font-size: 24px;
    justify-content: center;
}

</style>