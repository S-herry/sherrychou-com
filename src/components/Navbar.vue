<template>
  <nav class="w-full flex items-center justify-between px-8 py-4 bg-gradient-to-r from-gray-900 to-gray-800 shadow-lg border-b border-cyan-500/30">
    <div class="text-cyan-400 font-bold text-xl tracking-widest">SHERRY</div>
    <ul class="flex gap-8 text-gray-200 font-medium">
      <li><a href="/" class="hover:text-cyan-400 transition">首頁</a></li>
      <li><a href="/blog" class="hover:text-cyan-400 transition">部落格</a></li>
      <li><a href="/portfolio" class="hover:text-cyan-400 transition">作品集</a></li>
    </ul>
  </nav>
</template>

<script setup>
// 無需邏輯
</script>

<style scoped>
nav {
  font-family: 'Orbitron', 'Montserrat', 'sans-serif';
  letter-spacing: 0.1em;
}
</style>
