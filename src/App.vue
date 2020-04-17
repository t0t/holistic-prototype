<template>
  <div id="app">
    <Brand msg="TODH"/>
    <img alt="Cover" src="./assets/img1.jpg">
    <Wellcome msg="instantly prototype new ideas"/>
  </div>
</template>

<script>
import Brand from './components/Brand.vue'
import Wellcome from './components/Wellcome.vue'

export default {
  name: 'App',
  components: {
    Brand,
    Wellcome
  }
}
</script>


<style lang="scss">
@import "./styles/_main.scss";

#app {
  font-family: $primary_font;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $primary;
  margin-top: $size;
}
</style>
