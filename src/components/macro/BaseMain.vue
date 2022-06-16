<template>
  <div>
    <JumboUno />
    <ServiceSec />
  </div>
</template>

<script>
import JumboUno from "../sections/JumboUno.vue";
import ServiceSec from "../sections/ServiceSection.vue";

export default {
  name: "BaseMain",
  components: {
    JumboUno,
    ServiceSec,
  },
};
</script>

<style></style>
