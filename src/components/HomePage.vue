<template>
  <div class="relative max-w-4xl mx-auto px-4 py-8 overflow-hidden">
    <!-- 科技感背景特效 -->
    <div class="absolute inset-0 pointer-events-none z-0">
      <div class="w-96 h-96 bg-cyan-500/10 rounded-full blur-3xl animate-pulse absolute -top-32 -left-32"></div>
      <div class="w-80 h-80 bg-fuchsia-500/10 rounded-full blur-3xl animate-pulse absolute -bottom-32 -right-32"></div>
      <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/30 via-gray-900/60 to-fuchsia-900/30" />
    </div>
    <div class="relative z-10">
      <Hero />
    </div>
  </div>
</template>

<script setup>
import Hero from "./Hero.vue";
</script>