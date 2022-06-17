<template>
  <footer>
    <FooterTop />
    <FooterBottom />
  </footer>
</template>

<script>
import FooterTop from "../sections/FooterTop.vue";
import FooterBottom from "../sections/FooterBottom.vue";
export default {
  name: "BaseFooter",
  components: {
    FooterTop,
    FooterBottom,
  },
};
</script>

<style lang="scss" scoped>
footer {
  width: 1516px;
  overflow: hidden;
}
</style>
