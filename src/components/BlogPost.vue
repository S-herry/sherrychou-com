<template>
  <article class="prose prose-invert max-w-2xl mx-auto">
    <h1 class="text-cyan-300">{{ post.title }}</h1>
    <p class="text-gray-400 text-sm mb-4">{{ post.date }}</p>
    <div>{{ post.content }}</div>
  </article>
</template>

<script setup>
defineProps({
  post: {
    type: Object,
    required: true
  }
});
</script> 