<template lang="pug">
  #app
    head-bar
    main-content Development done right.
    social-links
</template>

<script>
import HeadBar from "./components/HeadBar.vue";
import MainContent from "./components/MainContent.vue";
import SocialLinks from "./components/SocialLinks.vue";

export default {
  components: {
    HeadBar,
    MainContent,
    SocialLinks
  }
};
</script>

<style lang="sass">
#app
  font-family: "Avenir", Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  color: #2A3D45

body
  margin: 0
</style>
