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
  position: fixed;
  width: 100%;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  margin: 0;
  color: $white;
}
.Brand img {
    max-width: 100px;
    margin: $size / 2;
}

</style>
