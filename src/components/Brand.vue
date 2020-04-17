<template>
  <div class="brand">
    <img alt="Vue logo" src="../assets/logo-todh-2.svg">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Brand',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}
img {
  max-width: 100px;
}

</style>
