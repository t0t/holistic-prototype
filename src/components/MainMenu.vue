<template>
  <nav class="MainMenu">
    <ul>
      <li>
        <IconMenu /> Artwork
      </li>
      <li>About</li>
      <li>TODH Project</li>
      <li>Contact</li>
    </ul>
  </nav>
</template>

<script>

import IconMenu from "./icons/IconMenu.vue";
export default {
  name: "MainMenu",
  components: {
    IconMenu,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../styles/main.scss";

.MainMenu {
  position: fixed;
  top: $size / 2;
  right: 0;
  //   padding: ($size / 8) 0;
  background-color: $primary;
}
</style>
