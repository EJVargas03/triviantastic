<script setup>
import useScore from '@/composables/useScore'
const { score } = useScore()
</script>

<template>
  <p class="score">Score: {{ score }}</p>
</template>

<style lang="postcss" scoped>
.score {
  @apply absolute bottom-6 right-8 text-2xl font-bold rounded-xl uppercase text-red-600 bg-white;
}
</style>
