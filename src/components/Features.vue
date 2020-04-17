<template>
  <div class="Features">
    <h2 class="FeaturesTitle">{{ msg }}</h2>
    <ul class="FeaturesList">
        <li> kjkjhb kjhb k</li>
        <li> kjkjhb kjhb k</li>
        <li> kjkjhb kjhb k</li>
        <li> kjkjhb kjhb k</li>
    </ul>
  </div>
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
  
  &Title { 
    width: 100%;
  }
}

</style>
