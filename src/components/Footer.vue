<template>
  <footer class="header">
    <div class="container">
      <div class="header_nav">
        <div class="header_nav_logo">
          <img
            class="header_nav_logo__imlogo"
            src="../assets/img/logo-exam.svg"
            alt="our logo"
          />
          <span class="header_nav_logo__name">Moments of air</span>
        </div>
        <ul class="header_nav_hrefs">
          <li class="header_nav_hrefs__elnav" style="list-style-type: none">
            <a
              class="header_nav__arrow"
              href="#"
              style="text-decoration: none; color: black"
            >
              Features
            </a>
            <!-- <span class="header_nav__arrow"></span> -->
            <ul class="header_nav_menu">
              <li>
                <a href="#" style="text-decoration: none; color: black">
                  Technologies
                </a>
              </li>
              <li>
                <a href="#" style="text-decoration: none; color: black">
                  Who we are
                </a>
              </li>
              <li>
                <a href="#" style="text-decoration: none; color: black">
                  How do we deliver
                </a>
              </li>
            </ul>
          </li>
          <li
            class="header_nav_hrefs__elnav elnav--visibility"
            style="list-style-type: none"
          >
            <a href="#" style="text-decoration: none; color: black">
              Technologies
            </a>
          </li>

          <li
            class="header_nav_hrefs__elnav elnav--visibility"
            style="list-style-type: none"
          >
            <a href="#" style="text-decoration: none; color: black">
              Who we are
            </a>
          </li>
          <li
            class="header_nav_hrefs__elnav elnav--visibility"
            style="list-style-type: none"
          >
            <a href="#" style="text-decoration: none; color: black">
              How do we deliver
            </a>
          </li>
        </ul>
        <Button
          class="header_nav__button"
          style="color: black; border: solid black 1px"
        ></Button>
      </div>
    </div>
  </footer>
</template>

<script>
import Button from "../components/Button.vue";
export default {
  components: {
    Button,
  },
};
</script>

<style lang="scss" scoped>
@import "./src/scss/_footer.scss";
</style>