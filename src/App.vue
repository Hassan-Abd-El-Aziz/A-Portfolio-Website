<template>
  <div class="bg-[#111827] min-h-screen">
    <NavBar />
    <HeroSection />
    <ServicesSection />
    <AboutSection />
    <ExperienceAndskills />
  </div>
</template>
<script setup>
import { defineAsyncComponent } from "vue";
// import Components Asynchronously
const NavBar = defineAsyncComponent(() => import("@/Components/NavBar.vue"));
const HeroSection = defineAsyncComponent(() =>
  import("@/Components/HeroSection.vue")
);
const ServicesSection = defineAsyncComponent(() =>
  import("@/Components/ServicesSection.vue")
);
const AboutSection = defineAsyncComponent(() =>
  import("@/Components/AboutSection.vue")
);
const ExperienceAndskills = defineAsyncComponent(() =>
  import("@/Components/ExperienceAndskills.vue")
);
</script>
