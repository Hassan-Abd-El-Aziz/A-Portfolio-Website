<template>
  <div class="bg-[#111827] min-h-screen">
    <NavBar />
    <HeroSection />
    <ServicesSection />
    <AboutSection />
    <ExperienceAndskills />
    <LatestProjSection />
    <ContactSection />
    <TestimonialsSection />
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

const LatestProjSection = defineAsyncComponent(() =>
  import("@/Components/LatestProjSectio.vue")
);
const ContactSection = defineAsyncComponent(() =>
  import("@/Components/ContactSection.vue")
);
const TestimonialsSection = defineAsyncComponent(() =>
  import("@/Components/TestimonialsSection.vue")
);
</script>
