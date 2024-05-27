<template>
  <h2 class="heading">Counter App</h2>
  <div class="container">
    <h3>The current count is...</h3>
    <div class="container-count">0</div>
    <div class="container-button">
      <button class="button">+</button>
      <button class="button">-</button>
    </div>
  </div>
</template>

<style scoped>
.heading {
  text-align: center;
  margin-bottom: 0.5rem;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 50vh;
  border: solid 1px green;
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
