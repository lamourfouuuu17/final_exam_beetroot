<template>
  <Header></Header>
  <SectionEssential></SectionEssential>
  <SectionDiscount></SectionDiscount>
  <SectionLock></SectionLock>
  <SectionStatistics></SectionStatistics>
  <SectionCinema></SectionCinema>
  <SectionShatter></SectionShatter>
  <SectionLisens></SectionLisens>
  <SectionDeliver></SectionDeliver>
  <!-- <SectionMap></SectionMap> -->
  <SectionContact></SectionContact>
  <Footer></Footer>
</template>

<script>
import Header from "./components/Header.vue";
import SectionEssential from "./components/SectionEssential.vue";
import SectionDiscount from "./components/SectionDiscount.vue";
import SectionLock from "./components/SectionLock.vue";
import SectionStatistics from "./components/SectionStatistics.vue";
import SectionCinema from "./components/SectionCinema.vue";
import SectionShatter from "./components/SectionShatter.vue";
import SectionLisens from "./components/SectionLisens.vue";
import SectionDeliver from "./components/SectionDeliver.vue";
// import SectionMap from "./components/SectionMap.vue";
import SectionContact from "./components/SectionContact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    SectionEssential,
    SectionDiscount,
    SectionLock,
    SectionStatistics,
    SectionCinema,
    SectionShatter,
    SectionLisens,
    SectionDeliver,
    // SectionMap,
    SectionContact,
    Footer,
  },
};
</script>

<style lang="scss">
html,
body {
  margin: 0;
  padding: 0;
}
#app {
  @import "./src/scss/_basis.scss";
}
</style>
