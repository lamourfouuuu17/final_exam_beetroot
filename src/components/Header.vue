<template>
  <link rel="preconnect" href="https://fonts.gstatic.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@700&display=swap"
    rel="stylesheet"
  />
  <link rel="preconnect" href="https://fonts.gstatic.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap"
    rel="stylesheet"
  />
  <header class="header">
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
              style="text-decoration: none; color: white"
            >
              Features
            </a>
            <!-- <span class="header_nav__arrow"></span> -->
            <ul class="header_nav_menu">
              <li>
                <a href="#" style="text-decoration: none; color: white">
                  Technologies
                </a>
              </li>
              <li>
                <a href="#" style="text-decoration: none; color: white">
                  Who we are
                </a>
              </li>
              <li>
                <a href="#" style="text-decoration: none; color: white">
                  How do we deliver
                </a>
              </li>
            </ul>
          </li>
          <li
            class="header_nav_hrefs__elnav elnav--visibility"
            style="list-style-type: none"
          >
            <a href="#" style="text-decoration: none; color: white">
              Technologies
            </a>
          </li>

          <li
            class="header_nav_hrefs__elnav elnav--visibility"
            style="list-style-type: none"
          >
            <a href="#" style="text-decoration: none; color: white">
              Who we are
            </a>
          </li>
          <li
            class="header_nav_hrefs__elnav elnav--visibility"
            style="list-style-type: none"
          >
            <a href="#" style="text-decoration: none; color: white">
              How do we deliver
            </a>
          </li>
        </ul>
        <Button class="header_nav__button"></Button>
      </div>
      <div class="header_info">
        <div class="header_info_titles">
          <h1 class="header_info_titles__main">
            Essential lens, filters, <br />
            and cases for drones
          </h1>
          <img
            class="header_info_titles__img"
            src="../assets/img/header-vector.svg"
            alt="vector"
          />
        </div>
        <div class="header_info_buttons">
          <Button class="header_info_buttons_btn"></Button>
          <span class="header_info_buttons_text">How do we deliver?</span>
          <circleButton></circleButton>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@import "./src/scss/_header.scss";
</style>

<script>
import Button from "../components/Button.vue";
import circleButton from "../components/circleButton.vue";

export default {
  components: {
    Button,
    circleButton,
  },
};
</script>

