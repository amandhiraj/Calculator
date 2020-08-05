<template>
  <div id="app">
    <h1>Simple Vue Calculator</h1>
    <p>By: Aman Dhiraj</p>
    <br>
    <Calculator></Calculator>
  </div>
</template>

<script>
import Calculator from "./components/Calculator.vue";

export default {
  name: "app",
  components: {
    Calculator,
  },
};
</script>

<style>
#app {
  font-family: "Courier New", Courier, monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #e74c3c;
  margin-top: 60px;
}

h1 {
  font-size: 3em;
}

img {
  max-width: 50px;
  max-height: 80px;
  height: 80px;
}
</style>
