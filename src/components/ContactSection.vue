<template>
  <div class="social-links">
    <div>
      <h2 class="social-links__title">Contact</h2>
    </div>
    <div class="social-links__row">
      <a href="https://github.com/patzick" target="_blank" class="social-link">
        <img
          class="social-link-icon"
          alt="GitHub"
          src="../assets/github-icon.svg"
        />
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
      </a>
      <a
        href="https://twitter.com/tomczykpatryk"
        target="_blank"
        class="social-link"
      >
        <img
          class="social-link-icon"
          alt="Twitter"
          src="../assets/twitter.svg"
        />
      </a>
    </div>

    <!-- <a href="mailto:contact@ifit.pt" class="social-link"> -->
    <!-- <img class="social-link-icon" alt="GitHub" src="../assets/mail.svg" /> -->
    <!-- <div class="social-link-title">contact@ifit.pt</div> -->
    <!-- </a> -->
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.social-links {
  display: flex;
  flex-basis: 100%;
  align-items: center;
  flex-direction: column;
  // padding: 2rem 1rem 1rem;
  justify-content: flex-end;
  width: 100%;

  &__row {
    display: flex;
  }
  &__title {
    color: #161e63;
    font-size: 14px;
    font-weight: 500;
    margin: 0;
    text-transform: uppercase;
  }

  .social-link {
    display: flex;
    text-decoration: none;
    margin: 0.5rem 0.5rem;

    .social-link-title {
      padding: 0 1rem;
      font-size: 1.2rem;
      color: #2a3d45;
    }
    &-icon {
      width: 20px;
    }
  }
}
</style>
