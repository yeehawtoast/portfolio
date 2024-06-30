<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="container">
    <span class="text">This is my Contact</span>

    <div class="yourform">
      <form class="form">
      <div class="title">Contact us</div>
      <input type="text" placeholder="Your email" class="input">
      <textarea placeholder="Your Message"></textarea>
      <button>Submit</button>
      </form>
    </div>
    
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
  .yourform{
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
  .form {
  position: relative;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  gap: 10px;
  width: 300px;
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 30px 30px -30px rgba(27, 26, 26, 0.315);
}

.form .title {
  color: royalblue;
  font-size: 30px;
  font-weight: 600;
  letter-spacing: -1px;
  line-height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.form input {
  outline: 0;
  border: 1px solid rgb(219, 213, 213);
  padding: 8px 14px;
  border-radius: 8px;
  width: 90%;
  height: 50px;
}

.form textarea {
  border-radius: 8px;
  height: 100px;
  width: 90%;
  resize: none;
  outline: 0;
  padding: 8px 14px;
  border: 1px solid rgb(219, 213, 213);
}

.form button {
  align-self: flex-end;
  padding: 8px;
  outline: 0;
  border: 0;
  border-radius: 8px;
  font-size: 16px;
  font-weight: 500;
  background-color: royalblue;
  color: #fff;
  cursor: pointer;
}

</style>