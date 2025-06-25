<template>
  <div class="relative max-w-4xl mx-auto px-4 py-8 overflow-hidden">
    <!-- 科技感背景特效 -->
    <div class="absolute inset-0 pointer-events-none z-0">
      <div class="w-80 h-80 bg-cyan-500/10 rounded-full blur-3xl animate-pulse absolute -top-24 -left-24"></div>
      <div class="w-72 h-72 bg-fuchsia-500/10 rounded-full blur-3xl animate-pulse absolute -bottom-24 -right-24"></div>
      <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/30 via-gray-900/60 to-fuchsia-900/30" />
    </div>
    <div class="relative z-10">
      <h1 class="text-3xl font-bold text-fuchsia-300 mb-8">作品集展示</h1>
      <div class="grid md:grid-cols-2 gap-8">
        <a href="/portfolio/interactive-a">
          <PortfolioCard image="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?auto=format&fit=crop&w=400&q=80" title="互動式作品 A" description="結合動畫與滑動互動的前端專案" />
        </a>
        <a href="/portfolio/tech-b">
          <PortfolioCard image="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" title="科技感網站 B" description="暗色系科技感設計網站" />
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
import PortfolioCard from './PortfolioCard.vue';
</script> 