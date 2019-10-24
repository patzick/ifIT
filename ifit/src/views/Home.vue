<template>
  <div>
    <main-content> Development done right. </main-content>
    <social-links />
  </div>
</template>

<script>
// @ is an alias to /src
import MainContent from "@/components/MainContent.vue";
import SocialLinks from "@/components/SocialLinks.vue";

export default {
  name: "home",
  components: {
    MainContent,
    SocialLinks
  }
};
</script>
