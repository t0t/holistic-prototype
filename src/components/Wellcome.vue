<template>
  <div class="Cover">
    <h2 class="CoverTitle">{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: 'Wellcome',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../styles/main.scss";

.Cover {
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  background-image: url('../assets/img1.jpg');
  background-size: cover;
  height: $size * 8;
  padding: $size / 2;
  &Title {
    color: $primary;
    font-size: 80px;
  }
}

</style>
