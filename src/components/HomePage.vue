<template>
  <div class="max-w-4xl mx-auto px-4 py-16 bg-bg rounded-xl shadow-sm">
    <Hero />
    <!-- 品牌色分隔 -->
    <div class="my-12 h-2 w-24 bg-primary rounded-full mx-auto"></div>
    <!-- About 區塊 -->
    <section class="flex flex-col md:flex-row items-center gap-8 py-8">
      <div class="flex-1 flex justify-center relative">
        <div class="absolute -top-4 -left-4 w-32 h-32 bg-primary rounded-full blur-xl -z-10"></div>
        <img src="https://undraw.co/api/illustrations/undraw_feeling_proud_qne1.svg" alt="About 插畫" class="w-48 md:w-64 h-auto" loading="lazy" />
      </div>
      <div class="flex-1">
        <h2 class="text-2xl font-bold text-accent mb-4">關於我</h2>
        <ul class="text-gray-700 space-y-2 mb-6">
          <li>・三年 Vue 前端開發經驗</li>
          <li>・熱愛 UI/UX 設計與動畫</li>
          <li>・擅長 RWD、互動設計</li>
          <li>・喜歡分享技術與寫作</li>
        </ul>
        <a href="mailto:youremail@example.com" class="inline-block bg-secondary text-white px-6 py-2 rounded-full font-semibold shadow hover:bg-accent hover:text-bg transition">聯絡我</a>
      </div>
    </section>
  </div>
</template>

<script setup>
import Hero from "./Hero.vue";
</script>