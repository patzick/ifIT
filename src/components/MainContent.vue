<template>
  <div class="main-content">
    <picture class="main-content__picture">
      <img class="main-content__picture--image" src="@/assets/ptomczyk.png" />
    </picture>
    <h1 class="main-content__header">
      <span class="main-content__header-light">Patryk</span>
      <span class="main-content__header-bolder">Tomczyk</span>
    </h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      image: ""
    };
  }
};
</script>

<style lang="sass" scoped>
.main-content
  display: flex
  justify-content: flex-end
  font-family: Roboto
  font-size: 2rem
  text-align: end
  position: relative
  &__picture
    position: absolute
    top: -12rem
    left: 14rem
    img
  &__picture--image
    width: 250px
    border: 1px solid white
    border-radius: 50%
  &__header
    color: white
    text-align: right
    font-weight: 800
    display: flex
    flex-direction: column
    margin: 0
    text-transform: uppercase
  &__header-light
      font-weight: 200
      line-height: 90px
  &__header-bolder
      font-size: 200px
      line-height: 190px

@media screen and (min-width: 900px)
    .main-content
      font-size: 4rem
</style>
