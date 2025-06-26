<template>
  <article class="max-w-2xl mx-auto bg-primary/60 rounded-2xl shadow-lg p-6">
    <div class="flex flex-col items-center mb-6">
      <img :src="work?.image" :alt="work?.title" class="w-full max-w-lg h-64 object-cover rounded-xl shadow border-4 border-bg mb-4" />
    </div>
    <h1 class="text-3xl font-bold text-accent mb-2 text-center">{{ work?.title }}</h1>
    <p class="text-secondary text-base mb-4 text-center">{{ work?.description }}</p>
    <div class="text-gray-700 leading-relaxed">{{ work?.content }}</div>
  </article>
</template>
<script setup>
defineProps({ work: Object });
</script>