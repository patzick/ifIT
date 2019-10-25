<template>
  <div id="app">
    <Home></Home>
  </div>
</template>

<script>
import Home from "./views/Home.vue";

export default {
  components: {
    Home
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Roboto", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2a3d45;
  background-color: #d9d9d9;
  height: 100vh;
  display: flex;
  justify-content: center;
}

body {
  margin: 0;
}
</style>
