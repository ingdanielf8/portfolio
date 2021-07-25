<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Estudios />
</template>

<script>
import Estudios from "./components/Estudios.vue";

export default {
  name: "App",
  components: {
    Estudios,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
