<template>
  <section class="flex flex-col items-center justify-center min-h-[60vh] text-center relative overflow-hidden">
    <h1 class="text-5xl md:text-7xl font-extrabold text-cyan-400 drop-shadow-glow animate-fadein">Hi, I am <span class="text-white">Sherry</span></h1>
    <p class="mt-6 text-lg md:text-2xl text-gray-300 animate-fadein-delay">前端開發者 | 科技感設計 | Vue & Astro</p>
    <div class="absolute inset-0 pointer-events-none">
      <div class="w-96 h-96 bg-cyan-500/10 rounded-full blur-3xl animate-pulse absolute -top-32 -left-32"></div>
      <div class="w-80 h-80 bg-fuchsia-500/10 rounded-full blur-3xl animate-pulse absolute -bottom-32 -right-32"></div>
    </div>
  </section>
</template>

<script setup>
// 動畫可用 animate.css 或自訂
</script>

<style scoped>
@keyframes fadein {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: none; }
}
.animate-fadein {
  animation: fadein 1s cubic-bezier(.4,0,.2,1) both;
}
.animate-fadein-delay {
  animation: fadein 1.5s cubic-bezier(.4,0,.2,1) both;
}
.drop-shadow-glow {
  filter: drop-shadow(0 0 16px #0ff) drop-shadow(0 0 32px #0ff3);
}
</style>
