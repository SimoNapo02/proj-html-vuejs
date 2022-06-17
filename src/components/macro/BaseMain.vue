<template>
  <div>
    <JumboUno />
    <ServiceSec />
    <CompanySection />
    <LogoSection />
  </div>
</template>

<script>
import JumboUno from "../sections/JumboUno.vue";
import ServiceSec from "../sections/ServiceSection.vue";
import CompanySection from "../sections/CompanySection.vue";
import LogoSection from "../sections/LogoSection.vue";

export default {
  name: "BaseMain",
  components: {
    JumboUno,
    ServiceSec,
    CompanySection,
    LogoSection,
  },
};
</script>

<style></style>
