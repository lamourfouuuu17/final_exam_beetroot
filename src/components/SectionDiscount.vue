<template>
  <section class="d-section">
    <div class="container">
      <div class="d-section_titles">
        <h2 class="d-section_titles__title">
          Buy a set with a
          <span class="d-section_titles__spa"> 30% </span> discount
        </h2>
        <p class="d-section_titles__prg">
          These baby filters make your drone look faster. Or at least you won’t
          lose them like <br />
          those other black filters
        </p>
      </div>

      <div
        class="d-component_products"
        style="display: flex; justify-content: space-between"
      >
        <DiscountComponent></DiscountComponent>
        <DiscountComponent2></DiscountComponent2>
        <DiscountComponent3></DiscountComponent3>
        <DiscountComponent4></DiscountComponent4>
      </div>
    </div>
  </section>
</template>

<script>
import DiscountComponent from "../components/DiscountComponent.vue";
import DiscountComponent2 from "../components/DiscountComponent2.vue";
import DiscountComponent3 from "../components/DiscountComponent3.vue";
import DiscountComponent4 from "../components/DiscountComponent4.vue";

export default {
  components: {
    DiscountComponent,
    DiscountComponent2,
    DiscountComponent3,
    DiscountComponent4,
  },
};
</script>

<style style lang="scss" scoped>
@import "./src/scss/_d-section.scss";
</style>