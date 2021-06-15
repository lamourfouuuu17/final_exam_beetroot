<template>
  <button class="btn">Buy a set</button>
</template>

<style lang="scss" scoped>
@import "./src/scss/_mixins.scss";
@import "./src/scss/_fonts.scss";

.btn {
  width: 160px;
  height: 54px;
  border-radius: 5px;
  border: solid 1px $coloryel;
  outline: none;
  background-color: transparent;
  @include fontMuseo;
  font-size: 16px;
  color: white;

  &:hover {
    transform: scale(1.1);
  }
}
@media (max-width: 320px) {
  .btn {
    font-size: 12px;
  }
}
</style>

<script>
export default {};
</script>