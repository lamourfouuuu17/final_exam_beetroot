<template>
  <section class="lis-section">
    <div class="container">
      <div class="lis-section_block">
        <img
          src="../assets/img/lis-section_img.png"
          alt="img"
          class="lis-section__img"
        />
        <div class="lis-section_txt">
          <h4 class="lis-section_txt__title">
            Just make <span class="lis-section_txt__span"> one click</span> and
            we will send you our set!
          </h4>
          <span class="lis-section_txt__spa">200 USD</span>
          <span class="lis-section_txt__spa lis-section_txt__spa--crossed"
            >270 USD</span
          >
          <Button class="lis-section_txt__btn"></Button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Button from "../components/Button.vue";
export default {
  components: {
    Button,
  },
};
</script>

<style style lang="scss" scoped>
@import "./src/scss/_lis-section.scss";
</style>
