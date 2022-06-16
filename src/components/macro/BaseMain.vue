<template>
  <div>
    <JumboUno />
    <Service />
  </div>
</template>

<script>
import JumboUno from "../sections/JumboUno.vue";
import Service from "../sections/ServiceSection.vue";

export default {
  name: "BaseMain",
  components: {
    JumboUno,
    Service,
  },
};
</script>

<style></style>
