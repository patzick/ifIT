<template>
  <div class="home">
    <main-content></main-content>
    <work-section></work-section>
    <contact-section />
  </div>
</template>

<script>
// @ is an alias to /src
import MainContent from "@/components/MainContent.vue";
import ContactSection from "@/components/ContactSection.vue";
import WorkSection from "@/components/WorkSection.vue";

export default {
  name: "home",
  components: {
    MainContent,
    WorkSection,
    ContactSection
  }
};
</script>
<style lang="scss" scoped>
.home {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
</style>
