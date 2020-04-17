<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="TODH"/>
    <Wellcome msg="instantly prototype new ideas"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Wellcome from './components/Wellcome.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Wellcome
  }
}
</script>


<style lang="scss">
@import "./styles/_variables.scss";

#app {
  font-family: $primary_font;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $primary;
  margin-top: $size;
}
</style>
