<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Compétences - Portfolio Audrey Gaborit',
  meta: [
    {
      name: 'description',
      content: 'Mes compétences techniques et humaines en développement web.',
    },
    { property: 'og:title', content: 'Compétences - Portfolio Audrey Gaborit' },
    {
      property: 'og:description',
      content: 'Mes compétences techniques et humaines en développement web.',
    },
  ],
})
</script>

<template>
  <h1 class="text-2xl font-semibold p-4">Compétences</h1>
</template>
