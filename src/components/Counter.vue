<template>
  <h2 class="heading">Counter App</h2>
  <div class="container">
    <h3>The current count is...</h3>
    <div class="container-count">{{ count }}</div>
    <div class="container-button">
      <button class="button" @click="count--">-</button>
      <button class="button" @click="count++">+</button>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const count = ref(0);
</script>

<style scoped>
.heading {
  text-align: center;
  margin-bottom: 0.5rem;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.container-count {
  margin: 10px;
  font-size: 20px;
}

.container-button {
  display: flex;
  justify-content: center;
  align-items: center;
}

.button {
  background-color: #04aa6d;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 10px;
  margin: 5px;
}
</style>
