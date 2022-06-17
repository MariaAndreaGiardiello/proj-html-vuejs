<template>
  <main>
    <HeroSection/>
    <LightCardSection/>
    <AboutCompanySection/>
    <DarkCardSection/>
    <LightCardSection2/>
    <LightCardSection3/>
  </main>
</template>

<script>
import HeroSection from './sections/HeroSection.vue';
import LightCardSection from './sections/LightCardSection.vue';
import AboutCompanySection from './sections/AboutCompanySection.vue';
import DarkCardSection from './sections/DarkCardSection.vue';
import LightCardSection2 from './sections/LightCardSection2.vue';
import LightCardSection3 from './sections/LightCardSection3.vue';

export default {
    name: "MainComponents",
    components: {
    HeroSection,
    LightCardSection,
    AboutCompanySection,
    DarkCardSection,
    LightCardSection2,
    LightCardSection3
}
}
</script>

<style lang="scss" scoped>

</style>