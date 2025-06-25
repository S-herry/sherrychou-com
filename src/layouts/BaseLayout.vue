<template>
  <html lang="zh-Hant">
    <head>
      <meta charset="utf-8" />
      <meta name="viewport" content="width=device-width" />
      <title>Sherry | Astro + Vue 科技感網站</title>
      <link rel="stylesheet" href="/src/styles/global.css" />
      <link
        href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Montserrat:wght@400;700&display=swap"
        rel="stylesheet"
      />
    </head>
    <body class="bg-gray-950 min-h-screen font-['Montserrat']">
      <Navbar />
      <main class="max-w-4xl mx-auto px-4 py-8">
        <slot />
      </main>
    </body>
  </html>
</template>

<script setup>
import Navbar from '../components/Navbar.vue';
</script>
