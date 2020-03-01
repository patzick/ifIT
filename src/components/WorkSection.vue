<template>
  <div class="work-section">
    <p class="work-section__title">
      Senior frontend developer @
      <a
        class="work-section__title--link"
        href="https://www.divante.com"
        target="_blank"
      >
        Divante</a
      >
    </p>
    <p class="work-section__title">
      Core member @
      <a
        href="https://www.vuestorefront.io/"
        class="work-section__title--link"
        target="_blank"
        >VueStorefront</a
      >
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.work-section {
  width: 100%;
  &__title {
    color: #161e63;
    margin: 10px 0 10px 0;
    font-weight: 700;
    font-size: 14px;
    @media (min-width: 480px) {
      font-size: 18px;
    }
    // text-align: right;
    &--link {
      color: white;
      text-decoration: none;
      cursor: pointer;
    }
  }
}
</style>
