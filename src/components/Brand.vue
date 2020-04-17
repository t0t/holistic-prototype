<template>
  <div class="Brand">
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
<style lang="scss">
@import "../styles/main.scss";

.Brand {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: $size / 2;
}
.Brand img {
    max-width: 200px;
    margin-right: $size;
}

</style>
