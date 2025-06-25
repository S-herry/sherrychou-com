<template>
  <div class="relative max-w-4xl mx-auto px-4 py-8 overflow-hidden">
    <!-- 科技感背景特效 -->
    <div class="absolute inset-0 pointer-events-none z-0">
      <div class="w-80 h-80 bg-cyan-500/10 rounded-full blur-3xl animate-pulse absolute -top-24 -left-24"></div>
      <div class="w-72 h-72 bg-fuchsia-500/10 rounded-full blur-3xl animate-pulse absolute -bottom-24 -right-24"></div>
      <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/30 via-gray-900/60 to-fuchsia-900/30" />
    </div>
    <div class="relative z-10">
      <h1 class="text-3xl font-bold text-cyan-300 mb-8">部落格文章</h1>
      <div class="grid md:grid-cols-2 gap-8">
        <a href="/blog/astro-vue3">
          <BlogCard title="Astro + Vue3 入門" description="如何用 Astro 與 Vue3 打造現代網站" date="2024-06-01" />
        </a>
        <a href="/blog/tailwind-tech">
          <BlogCard title="Tailwind CSS 科技感設計" description="用 Tailwind 打造暗色科技感 UI" date="2024-06-02" />
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
import BlogCard from './BlogCard.vue';
</script> 