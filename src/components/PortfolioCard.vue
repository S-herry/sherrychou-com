<template>
  <div class="bg-gradient-to-br from-gray-900 to-gray-800 border border-fuchsia-500/30 rounded-xl p-6 shadow-lg transition-transform hover:-translate-y-2 hover:shadow-fuchsia-500/30 animate-slidein">
    <img :src="image" :alt="title" class="w-full h-40 object-cover rounded mb-4 border-b border-fuchsia-400/20" />
    <h2 class="text-xl font-bold text-fuchsia-300 mb-2">{{ title }}</h2>
    <p class="text-gray-300">{{ description }}</p>
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
@keyframes slidein {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: none; }
}
.animate-slidein {
  animation: slidein 1s cubic-bezier(.4,0,.2,1) both;
}
</style>
