<template>
  <div class="max-w-4xl mx-auto px-4 py-12 bg-bg rounded-xl shadow-sm">
    <h1 class="text-3xl font-bold text-accent mb-8">作品集展示</h1>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8" data-aos="fade-up">
      <a href="/portfolio/interactive-a">
        <PortfolioCard image="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?auto=format&fit=crop&w=400&q=80" title="互動式作品 A" description="結合動畫與滑動互動的前端專案" />
      </a>
      <a href="/portfolio/tech-b">
        <PortfolioCard image="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" title="科技感網站 B" description="暗色系科技感設計網站" />
      </a>
      <a href="/portfolio/tech-b">
        <PortfolioCard image="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" title="科技感網站 B" description="暗色系科技感設計網站" />
      </a>
      <a href="/portfolio/tech-b">
        <PortfolioCard image="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" title="科技感網站 B" description="暗色系科技感設計網站" />
      </a>
    </div>
  </div>
</template>

<script setup>
import PortfolioCard from './PortfolioCard.vue';
</script> 