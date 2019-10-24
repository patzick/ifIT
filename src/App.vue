<template>
  <div id="app">
    <head-bar />
    <router-view />
  </div>
</template>

<script>
import HeadBar from "./components/HeadBar.vue";

export default {
  components: {
    HeadBar
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2a3d45;
}

body {
  margin: 0;
}
</style>
