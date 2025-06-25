

<template>
  <article class="prose prose-invert max-w-2xl mx-auto">
    <h1 class="text-fuchsia-300">{{ work?.title }}</h1>
    <img :src="work?.image" :alt="work?.title" class="rounded-xl my-6 border-b border-fuchsia-400/20" />
    <p class="text-gray-400 text-sm mb-4">{{ work?.description }}</p>
    <div>{{ work?.content }}</div>
  </article>
</template>
<script setup>
defineProps({ work: Object });
</script>