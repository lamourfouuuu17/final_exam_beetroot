<template>
  <section class="sh-section">
    <div class="container" style="position: relative">
      <div class="sh-section_first">
        <img
          src="../assets/img/sh-section_img.svg"
          alt="img"
          class="sh-section_first__img"
        />
        <div class="sh-section_first_txt">
          <img
            class="sh-section_first_txt__vector"
            src="../assets/img/sh-section_vector.svg"
            alt="vector"
            style="margin-bottom: -86px"
          />
          <h2 class="sh-section_first_txt__title">Shatterproof Construction</h2>
          <p class="sh-section_first_txt__prg" style="line-height: 23px">
            Ready for whatever you can throw at them with advanced hydrophobic
            coatings, scratch resistant glass, and shatterproof construction.
            From Brooklyn to Iceland, these filters are prepared for takeoff
            wherever you feel like flying.
          </p>
        </div>
      </div>
      <div class="sh-section_second">
        <div class="sh-section_second_txt">
          <h2 class="sh-section_second_txt__title">Who we are?</h2>
          <p class="sh-section_second_txt__prg" style="line-height: 23px">
            Ready for whatever you can throw at them with advanced hydrophobic
            coatings, scratch resistant glass, and shatterproof construction.
            From Brooklyn to Iceland, these filters are prepared for takeoff
            wherever you feel like flying.
          </p>
          <div class="sh-section_second_txt_more" style="margin-top: 46px">
            <div class="sh-section_second_txt_learn">Learn more</div>
            <circleButton></circleButton>
          </div>
        </div>
        <img
          src="../assets/img/sh-section_img2.svg"
          alt="img"
          class="sh-section_second__img"
        />
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
@import "./src/scss/_sh-section.scss";
</style>
