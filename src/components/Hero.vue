<template>
  <section class="flex flex-col md:flex-row items-center justify-between min-h-[60vh] text-center md:text-left gap-8 relative overflow-visible">
    <!-- 左側：自我介紹 -->
    <div class="flex-1 z-10 flex flex-col items-center md:items-start">
      <h1 class="text-4xl md:text-6xl font-extrabold text-accent mb-4">Hi, I am <span class="text-secondary">Sherry</span></h1>
      <p class="mt-2 text-lg md:text-2xl text-gray-700 mb-6">前端開發者 | Vue & Astro | 喜歡設計與動畫</p>
      <div class="flex gap-4 mb-6">
        <a href="https://github.com/" target="_blank" class="text-accent hover:text-secondary transition text-2xl"><i class="fa-brands fa-github"></i></a>
        <a href="https://linkedin.com/" target="_blank" class="text-accent hover:text-secondary transition text-2xl"><i class="fa-brands fa-linkedin"></i></a>
        <a href="mailto:youremail@example.com" class="text-accent hover:text-secondary transition text-2xl"><i class="fa-solid fa-envelope"></i></a>
      </div>
      <a href="/cv.pdf" class="inline-block bg-primary text-accent px-6 py-2 rounded-full font-semibold shadow hover:bg-secondary hover:text-white transition">下載履歷</a>
    </div>
    <!-- 右側：插畫 -->
    <div class="flex-1 flex justify-center md:justify-end z-10">
      <div class="relative">
        <div class="absolute -top-6 -left-6 w-40 h-40 bg-primary rounded-full blur-xl -z-10"></div>
        <img src="https://undraw.co/api/illustrations/undraw_programming_re_kg9v.svg" alt="插畫" class="w-64 md:w-80 h-auto" loading="lazy" />
      </div>
    </div>
    <!-- 背景品牌色圓形 -->
    <div class="absolute -top-16 -left-16 w-60 h-60 bg-primary/60 rounded-full blur-2xl z-0"></div>
    <div class="absolute -bottom-16 -right-16 w-72 h-72 bg-secondary/30 rounded-full blur-2xl z-0"></div>
  </section>
</template>

<script setup>
// 動畫可用 animate.css 或自訂
</script>

<style scoped>
/* 無需自訂動畫，RWD 交給 Tailwind */
</style>
