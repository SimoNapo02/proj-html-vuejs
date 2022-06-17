<template>
  <div>
    <JumboUno />
    <ServiceSec />
    <CompanySection />
    <LogoSection />
    <NewsSection />
    <KnowSection />
  </div>
</template>

<script>
import JumboUno from "../sections/JumboUno.vue";
import ServiceSec from "../sections/ServiceSection.vue";
import CompanySection from "../sections/CompanySection.vue";
import LogoSection from "../sections/LogoSection.vue";
import NewsSection from "../sections/NewsSection.vue";
import KnowSection from "../sections/KnowSection.vue";

export default {
  name: "BaseMain",
  components: {
    JumboUno,
    ServiceSec,
    CompanySection,
    LogoSection,
    NewsSection,
    KnowSection,
  },
};
</script>

<style></style>
