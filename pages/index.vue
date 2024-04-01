<template>
  <LandingContainer>
    <LandingHero></LandingHero>
    <LandingFeatures></LandingFeatures>
    <LandingLogos></LandingLogos>
    <LandingCta></LandingCta>
  </LandingContainer>
</template>

<!-- <script setup lang="ts">
definePageMeta({
  layout: "landing",
});

const nuxtApp = useNuxtApp();
const loading = ref(true);

nuxtApp.hook("page:start", () => {
  loading.value = true;
});

nuxtApp.hook("page:finish", () => {
  setTimeout(() => {
    loading.value = false;
  }, 3000);
});
</script> -->

<script>
definePageMeta({
  layout: "landing",
});
</script>
<style scoped>
.slide-enter-active,
.slide-leave-active {
  transition: top 0.5s ease-in-out;
}

.slide-enter-from,
.slide-leave-to {
  top: -100%; /* Slide in from top */
}

.slide-enter-to,
.slide-leave-from {
  top: 0; /* Slide out to bottom */
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}
</style>
