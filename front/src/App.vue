<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="text-center bg-gray-100 p-5">
    <p class="text-6xl text-red-700">Hello!</p>
    <h1 class="text-4xl text-green-500">Vite + TailwindCSS</h1>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
