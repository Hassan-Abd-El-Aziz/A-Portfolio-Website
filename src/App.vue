<template>
  <div class="bg-[#111827] min-h-screen">
    <NavBar />
  </div>
</template>
<script setup>
import { defineAsyncComponent } from 'vue';
// import Components Asynchronously
const NavBar=defineAsyncComponent(()=>import('@/Components/NavBar.vue'))
</script>
