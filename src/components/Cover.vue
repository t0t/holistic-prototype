<template>
  <section class="Cover">
    <h2 class="CoverTitle">{{ msg }}</h2>
    <h3 class="CoverSubtitle">Thoughts become things</h3>
  </section>
</template>

<script>
export default {
  name: 'Cover',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../styles/main.scss";

.Cover {
  // display: flex;
  background-image: url('../assets/img2.jpg');
  background-position: left;
  height: 100vh;
  padding: $size / 2;
}

.CoverTitle {
  margin-top: 100px;
  text-align: left;
  width: 50%;
  color: $primary;
  font-size: 80px;
}

.CoverSubtitle {
  text-align: left;
  width: 100%;
  color: $white;
}

</style>
