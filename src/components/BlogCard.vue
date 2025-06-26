<template>
  <div class="bg-primary border border-accent/30 rounded-xl p-6 shadow-sm transition-transform hover:-translate-y-1 hover:shadow-lg hover:border-secondary/60 group">
    <h2 class="text-2xl font-bold text-accent mb-2">{{ title }}</h2>
    <p class="text-gray-700 mb-4">{{ description }}</p>
    <span class="text-xs text-secondary">{{ date }}</span>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  description: String,
  date: String
});
</script>

<style scoped>
/* 移除動畫與螢光色 */
</style>
