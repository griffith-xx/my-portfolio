<script setup>
import Home from "@/components/Home.vue";
import AboutMe from "@/components/AboutMe.vue";
import Portfolio from "@/components/Portfolio.vue";
</script>

<template>
  <div class="bg-base-100 container mx-auto px-6 md:px-7 lg:px-8">
    <nav class="bg-base-200 flex justify-center items-center gap-8 py-6">
      <a class="font-bold hover:underline" href="#home">#</a>
      <a class="font-bold hover:underline" href="#about">เกี่ยวกับผม</a>
      <a class="font-bold hover:underline" href="#portfolio">ผลงาน</a>
    </nav>
    <Home />
    <AboutMe />
    <Portfolio />
  </div>
</template>
