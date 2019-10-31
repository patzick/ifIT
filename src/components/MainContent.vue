<template>
  <div class="main-content">
    <div class="main-content__picture">
      <div>
        <img class="main-content__picture--image" src="@/assets/ptomczyk.png" />
      </div>
    </div>

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

<style lang="scss" scoped>
.main-content {
  display: flex;
  justify-content: flex-end;
  font-family: "Roboto";
  font-size: 2rem;
  text-align: end;
  position: relative;
  justify-content: center;
  flex-direction: column;
  align-items: flex-end;

  &__picture--image {
    max-width: 50%;
    border: 1px solid white;
    border-radius: 50%;
    // position: relative;
    box-shadow: 0 0 0 7px #d9d9d9, 0 0 0 9px white;
  }
  &__header {
    color: white;
    text-align: right;
    font-weight: 800;
    display: flex;
    flex-direction: column;
    margin: 0;
    text-transform: uppercase;
  }
  &__header-light {
    font-weight: 200;
    font-size: calc(42px + (60 - 42) * ((100vw - 300px) / (1600 - 300)));
    // line-height: 90px;
  }
  &__header-bolder {
    font-size: calc(60px + (200 - 60) * ((100vw - 300px) / (1600 - 300)));
    position: relative;
    z-index: 2;
    &:before {
      content: "";
      display: block;
      width: 100%;
      height: 5px;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      z-index: -1;
      background-color: rgba(255, 234, 40);
    }
  }
}
</style>
