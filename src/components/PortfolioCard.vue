<template>
  <div class="bg-primary border border-accent/30 rounded-xl p-6 shadow-sm transition-transform hover:-translate-y-1 hover:shadow-lg hover:border-secondary/60 group flex flex-col h-80">
    <img :src="image" :alt="title" class="w-full h-32 object-cover rounded-lg mb-4 border-b border-secondary/30 group-hover:border-accent/40 transition" />
    <div class="flex-1 flex flex-col ">
      <h2 class="text-xl font-bold text-accent mb-2 line-clamp-1">{{ title }}</h2>
      <p class="text-gray-700 text-sm line-clamp-3">{{ description }}</p>
    </div>
  </div>
</template>

<script setup>
defineProps({
  image: String,
  title: String,
  description: String
});
</script>

<style scoped>
/* 移除動畫與螢光色 */
</style>
