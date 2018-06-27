<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <hello-world/>
  </div>
</template>

<script>
import test from "./components/hello-world";

export default {
  name: "App",
  components: {
    "hello-world":test
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
