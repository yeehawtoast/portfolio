<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>

  <div class='container'>

    <div class="mainscreen">
      <div class="hero">
        <span class="imagedot"></span>

      </div>
      <span class="text">Howdy! I'm Chris</span>
      <button class="viewbutton">View My Work</button>
    </div>

  </div>
</template>

<style scoped>
.container {
  height: 100vh;
}
.mainscreen{
  position: relative;
  align-self: center;
  justify-self: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  line-height: normal;
  width: fit-content;
  height: auto;
  margin-left: auto;
  margin-right: auto;
  color: #fafafa;
  font-weight: 300;
  z-index: 999;
}

.hero {
  display: flex;
  flex-direction: row;
  justify-content: center;
  margin-top: 100px;
  margin-bottom: 10px;
}

.text {
  display: flex;
  color: white;
  font-family: Montserrat, sans-serif;
  font-size: 72px;
  justify-content: center;
}

.imagedot {
  height: 200px;
  width: 200px;
  background-color: white;
  border-radius: 50%;
  display: inline-block;

}

.viewbutton{
  position: relative;
  display: flex;
  align-items: center;
  margin-top: 2.4rem;
  padding: 0.8rem 3rem;
  width: 27.5rem;
  height: 4.8rem;
  background-color: rgba(26,26,26,0.6);
  border: 2px solid #ff4d5a;
  border-radius: 2px;
  color: #ff4d5a;
  font-size: 2.4rem;
  font-weight: 500;
  cursor: pointer;
  animation: moveInBottom 0.7s 1.2s;
    animation-timing-function: ease;
    animation-fill-mode: none;
  animation-fill-mode: backwards;
  animation-timing-function: cubic-bezier(0.21, 1.11, 0.81, 0.99);
}
</style>