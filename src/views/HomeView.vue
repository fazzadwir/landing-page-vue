<template>
  <Hero></Hero>
  <HeroCard></HeroCard>
  <LoremCard></LoremCard>
  <AboutUs></AboutUs>
  <AboutUsPos></AboutUsPos>
  <FamiliyPos></FamiliyPos>
  <ServiceSection></ServiceSection>
  <ContactSection></ContactSection>
</template>

<script>
// @ is an alias to /src
import AboutUs from "@/components/AboutUs.vue";
import AboutUsPos from "@/components/AboutUsPos.vue";
import FamiliyPos from "@/components/FamiliyPos.vue";
import Hero from "@/components/Hero.vue";
import HeroCard from "@/components/HeroCard.vue";
import LoremCard from "@/components/LoremCard.vue";
import ServiceSection from "@/components/ServiceSection.vue";
import ContactSection from "@/components/ContactSection.vue";

export default {
  name: "HomeView",
  components: {
    AboutUs,
    AboutUsPos,
    FamiliyPos,
    Hero,
    HeroCard,
    LoremCard,
    ServiceSection,
    ContactSection,
  },
};
</script>
