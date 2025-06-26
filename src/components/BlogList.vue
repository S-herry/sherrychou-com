<template>
  <div class="max-w-4xl mx-auto px-4 py-12 bg-bg rounded-xl shadow-sm">
    <h1 class="text-3xl font-bold text-accent mb-8 text-center">部落格文章</h1>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8" data-aos="fade-up">
      <a href="/blog/astro-vue3">
        <BlogCard title="Astro + Vue3 入門" description="如何用 Astro 與 Vue3 打造現代網站" date="2024-06-01" />
      </a>
      <a href="/blog/tailwind-tech">
        <BlogCard title="Tailwind CSS 科技感設計" description="用 Tailwind 打造暗色科技感 UI" date="2024-06-02" />
      </a>
    </div>
  </div>
</template>

<script setup>
import BlogCard from './BlogCard.vue';
</script> 