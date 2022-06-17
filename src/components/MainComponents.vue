<template>
  <main>
    <HeroSection/>
    <LightCardSection/>
    <AboutCompanySection/>
    <DarkCardSection/>
  </main>
</template>

<script>
import HeroSection from './sections/HeroSection.vue';
import LightCardSection from './sections/LightCardSection.vue';
import AboutCompanySection from './sections/AboutCompanySection.vue';
import DarkCardSection from './sections/DarkCardSection.vue';

export default {
    name: "MainComponents",
    components: {
    HeroSection,
    LightCardSection,
    AboutCompanySection,
    DarkCardSection,
}
}
</script>

<style lang="scss" scoped>

</style>