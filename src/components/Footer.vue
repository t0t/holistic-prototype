<template>
  <div class="Footer">
    <img alt="Vue logo" src="../assets/logo-todh-2.svg">
    <small>{{ msg }}</small>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../styles/main.scss";

.Footer {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: $size / 2;
}
.Footer img {
    max-width: 20px;
    margin-right: $size / 4;
}

</style>
