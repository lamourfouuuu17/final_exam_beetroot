<template>
  <button class="btn-circle"></button>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.btn-circle {
  position: relative;
  display: inline;
  width: 39px;
  height: 39px;
  border: none;
  border-radius: 50%;
  border: solid 1px white;
  outline: none;
  background-color: transparent;
  margin-left: 20px;
  &:hover {
    opacity: 0.5;
  }
  &::after {
    position: absolute;
    top: 13.26px;
    left: 12.38px;
    content: "";
    display: block;
    width: 8px;
    height: 8px;
    border-right: 1px solid white;
    border-top: 1px solid white;
    transform: rotate(45deg);
    &:hover {
      opacity: 0.5;
    }
  }
}

@media (max-width: 480px) {
  .btn-circle {
    margin: 0;
  }
}
</style>