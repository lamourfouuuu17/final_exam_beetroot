<template>
  <section style="text-align: center">
    <figure class="chart" data-percent="75">
      <figcaption><div class="circle_span">1250</div></figcaption>

      <svg width="200" height="200">
        <circle
          class="outer"
          cx="120"
          cy="70"
          r="67"
          transform="rotate(-90, 95, 95)"
        />
      </svg>

      <div class="chart__text">Sets were delivered</div>
      <div class="chart__line"></div>
    </figure>

    <figure class="chart" data-percent="50">
      <figcaption><div class="circle_span">748</div></figcaption>
      <svg width="140" height="140">
        <circle
          class="outer"
          cx="120"
          cy="70"
          r="67"
          transform="rotate(-90, 95, 95)"
        />
      </svg>

      <div class="chart__text">People love us</div>
      <div class="chart__line"></div>
    </figure>

    <figure class="chart" data-percent="25">
      <figcaption><div class="circle_span">15</div></figcaption>
      <svg width="200" height="200">
        <circle
          class="outer"
          cx="120"
          cy="70"
          r="67"
          transform="rotate(-90, 95, 95)"
        />
      </svg>
      <div class="chart__text">Sets we had to return</div>
      <div class="chart__line"></div>
    </figure>
  </section>
</template>

<script>
export default {};
</script>

<style style lang="scss" scoped>
@import "./src/scss/_circleComponent.scss";
</style>