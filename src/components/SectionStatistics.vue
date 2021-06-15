<template>
  <section class="s-section">
    <div class="container" style="padding-top: 36px">
      <h2 class="s-section__title">
        Our <span class="s-section__spa">statistics</span>
      </h2>
      <CircleComponent></CircleComponent>
    </div>
  </section>
</template>

<script>
import CircleComponent from "../components/CircleComponent.vue";

export default {
  components: {
    CircleComponent,
  },
};
</script>

<style style lang="scss" scoped>
@import "./src/scss/_s-section.scss";
</style>