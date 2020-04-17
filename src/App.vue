<template>
  <div id="app">
    <Brand msg="TODH"/>
    <Wellcome msg="Instantly prototyping new ideas"/>
    <Features msg="Listado de servicios"/>
  </div>
</template>

<script>
import Brand from './components/Brand.vue'
import Wellcome from './components/Wellcome.vue'
import Features from './components/Features.vue'

export default {
  name: 'App',
  components: {
    Brand,
    Wellcome,
    Features
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
  margin-top: $size / 2;
}
</style>
