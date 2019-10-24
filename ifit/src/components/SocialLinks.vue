<template>
  <div class="social-links">
    <a href="https://github.com/patzick" target="_blank" class="social-link">
      <img class="social-link-icon" alt="GitHub" src="../assets/github.svg" />
      <div class="social-link-title">patzick</div>
    </a>
    <a
      href="https://www.linkedin.com/in/patryk-tomczyk-998763b3/"
      target="_blank"
      class="social-link"
    >
      <img
        class="social-link-icon"
        alt="LinkedIn"
        src="../assets/linkedin.svg"
      />
      <div class="social-link-title">Patryk Tomczyk</div>
    </a>
    <a href="mailto:contact@ifit.pt" class="social-link">
      <img class="social-link-icon" alt="GitHub" src="../assets/mail.svg" />
      <div class="social-link-title">contact@ifit.pt</div>
    </a>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style lang="sass" scoped>
.social-links
  display: flex
  flex-direction: column
  padding: 2rem 1rem 1rem
  .social-link
    display: flex
    text-decoration: none
    margin: 0.5rem 0
    .social-link-title
      padding: 0 1rem
      font-size: 1.2rem
      color: #2A3D45
</style>
