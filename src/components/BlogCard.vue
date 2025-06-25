<template>
  <div class="bg-gradient-to-br from-gray-800 to-gray-900 border border-cyan-500/30 rounded-xl p-6 shadow-lg transition-transform hover:-translate-y-2 hover:shadow-cyan-500/30 animate-slidein">
    <h2 class="text-2xl font-bold text-cyan-300 mb-2">{{ title }}</h2>
    <p class="text-gray-300 mb-4">{{ description }}</p>
    <span class="text-xs text-gray-500">{{ date }}</span>
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
@keyframes slidein {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: none; }
}
.animate-slidein {
  animation: slidein 1s cubic-bezier(.4,0,.2,1) both;
}
</style>
