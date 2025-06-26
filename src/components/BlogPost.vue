<template>
  <article class="max-w-2xl mx-auto bg-primary/60 rounded-2xl shadow-lg p-6">
    <div class="flex flex-col items-center mb-6">
      <img :src="post.image" :alt="post.title" class="w-full max-w-lg h-64 object-cover rounded-xl shadow border-4 border-bg mb-4" />
    </div>
    <h1 class="text-3xl font-bold text-accent mb-2 text-center">{{ post.title }}</h1>
    <p class="text-secondary text-base mb-2 text-center">{{ post.date }}</p>
    <p class="text-gray-700 text-base mb-4 text-center">{{ post.description }}</p>
    <div class="text-gray-700 leading-relaxed">{{ post.content }}</div>
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