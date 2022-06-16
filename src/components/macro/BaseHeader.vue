<template>
  <div class="header">
    <HeaderTop />
    <HeaderBottom />
  </div>
</template>

<script>
import HeaderTop from "../sections/HeaderTop.vue";
import HeaderBottom from "../sections/HeaderBottom.vue";

export default {
  name: "BaseHeader",
  components: {
    HeaderTop,
    HeaderBottom,
  },
};
</script>
<style scoped></style>
