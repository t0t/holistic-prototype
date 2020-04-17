<template>
  <div id="app">
    <Brand msg="TODH"/>
    <Cover msg="Instantly prototyping new ideas"/>
    <Features msg="Listado de servicios"/>
    <Gallery msg="Galería de fotos"/>
    <Footer msg="By Sergio Fores - 2020"/>
  </div>
</template>

<script>
import Brand from './components/Brand.vue'
import Cover from './components/Cover.vue'
import Features from './components/Features.vue'
import Gallery from './components/Gallery.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Brand,
    Cover,
    Features,
    Gallery,
    Footer
  }
}
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
