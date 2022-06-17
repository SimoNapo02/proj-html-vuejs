<template>
  <div>
    <JumboUno />
    <ServiceSec />
    <CompanySection />
  </div>
</template>

<script>
import JumboUno from "../sections/JumboUno.vue";
import ServiceSec from "../sections/ServiceSection.vue";
import CompanySection from "../sections/CompanySection.vue";

export default {
  name: "BaseMain",
  components: {
    JumboUno,
    ServiceSec,
    CompanySection,
  },
};
</script>

<style></style>
