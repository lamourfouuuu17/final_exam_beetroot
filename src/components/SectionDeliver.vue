<template>
  <section class="del-section">
    <div class="container" style="padding-right: 160px">
      <div class="del-section_block">
        <div class="del-section_txt">
          <img
            src="../assets/img/del-section_vector.svg"
            alt="img"
            class="del-section_txt__img"
          />
          <h4 class="del-section_txt__title">
            How do we <span class="del-section_txt__span"> deliver?</span>
          </h4>
          <div class="del-section_txt__more" style="margin-top: 46px">
            <div class="del-section_txt__learn">Learn more</div>
            <circleButton></circleButton>
          </div>
        </div>
        <div class="del-section_prg">
          <p class="del-section_prg_prgh">
            Your order is important to us! We make every effort to deliver your
            order in a timely manner. Before you place your order, please read
            through the various delivery options and pick the method that best
            suits your needs. Questions? Send us a quick email to
            orders@bdel.com and we'll get you an answer promptly.
          </p>
          <p class="del-section_prg_prgh" style="margin-top: 30px">
            Most orders are shipped the next business day after we receive your
            order.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import circleButton from "../components/circleButton.vue";

export default {
  components: {
    circleButton,
  },
};
</script>

<style style lang="scss" scoped>
@import "./src/scss/_del-section.scss";
</style>
