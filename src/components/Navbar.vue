<template>
  <nav class="w-full flex items-center justify-between px-8 py-4 bg-bg border-b border-primary">
    <div class="text-accent font-bold text-xl tracking-wide">SHERRY</div>
    <ul class="flex gap-8 text-accent font-medium">
      <li><a href="/" class="hover:text-secondary transition">首頁</a></li>
      <li><a href="/blog" class="hover:text-secondary transition">部落格</a></li>
      <li><a href="/portfolio" class="hover:text-secondary transition">作品集</a></li>
    </ul>
  </nav>
</template>

<script setup>
// 無需邏輯
</script>

<style scoped>
nav {
  font-family: 'Montserrat', 'sans-serif';
  letter-spacing: 0.02em;
}
</style>
