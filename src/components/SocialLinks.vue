<template>
  <ul class="SocialLinks">
    <li>
      <a href="https://www.instagram.com/t.o.d.h/" target="_blank"><IconInstagram /></a>
      <a href="https://www.linkedin.com/in/sergiofores/" target="_blank"><IconLinkedin /></a>
      <a href="https://medium.com/@todh" target="_blank"><IconMedium /></a>
      <a href="https://twitter.com/t0tinspire" target="_blank"><IconTwitter /></a>
      <a href="https://github.com/t0t" target="_blank"><IconGithub /></a>
      <a href="https://www.facebook.com/TODH-2139705836275088" target="_blank"><IconFacebook /></a>
    </li>
  </ul>
</template>

<script>
import IconLinkedin from "./icons/IconLinkedin.vue";
import IconInstagram from "./icons/IconInstagram.vue";
import IconMedium from "./icons/IconMedium.vue";
import IconTwitter from "./icons/IconTwitter.vue";
import IconGithub from "./icons/IconGithub.vue";
import IconFacebook from "./icons/IconFacebook.vue";

export default {
  name: "SocialLinks",
  components: {
    IconLinkedin,
    IconInstagram,
    IconMedium,
    IconTwitter,
    IconGithub,
    IconFacebook,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../styles/main.scss";

.SocialLinks {
  padding: ($size / 8) 0;
  a {
    margin-right: 10px;
    svg path {
      fill: $dark-grey;
      &:hover {
        fill: $grey;
      }
    }
  }
}
</style>
