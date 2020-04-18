<template>
  <section class="Features">
    <img alt="Feature img" src="../assets/grafico-1.svg">
    <h2 class="FeaturesTitle">{{ msg }}</h2>
    <ul class="FeaturesList">
        <li>Djkjhb kjhb k</li>
        <li>Djkjhb kjhb k</li>
        <li>Kds shf wjhgv  kjhb k</li>
        <li>Djkjhb kjhb k</li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'Features',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../styles/main.scss";

.Features {
  padding: $size / 2;
  display: block;

  img {
    max-height: 100px;
  }
  
  &Title { 
    width: 100%;
  }
}

</style>
