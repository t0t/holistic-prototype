<template>
  <div id="app">
    <Brand />
    <MainMenu />
    <Cover msg="Sergio Forés" />
    <Features msg="Áreas de investigación" />
    <Gallery msg="Artwork" />
    <Footer msg="Sergio Forés" />
  </div>
</template>

<script>
import MainMenu from "./components/MainMenu.vue";
import Brand from "./components/Brand.vue";
import Cover from "./components/Cover.vue";
import Features from "./components/Features.vue";
import Gallery from "./components/Gallery.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    MainMenu,
    Brand,
    Cover,
    Features,
    Gallery,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./styles/main.scss";

#app {
  font-family: $primary_font;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  // margin-top: $size / 2;
}
</style>
