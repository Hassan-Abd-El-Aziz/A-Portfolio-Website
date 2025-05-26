<template>
  <div class="bg-[#111827] min-h-screen">
    <NavBar />
    <HeroSection />
  </div>
</template>
<script setup>
import { defineAsyncComponent } from "vue";
// import Components Asynchronously
const NavBar = defineAsyncComponent(() => import("@/Components/NavBar.vue"));
const HeroSection = defineAsyncComponent(() =>
  import("@/Components/HeroSection.vue")
);
</script>
