<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Projets - Portfolio Audrey Gaborit',
  meta: [
    { name: 'description', content: 'Découvrez mes projets réalisés en tant que développeuse.' },
    { property: 'og:title', content: 'Projets - Portfolio Audrey Gaborit' },
    {
      property: 'og:description',
      content: 'Découvrez mes projets réalisés en tant que développeuse.',
    },
  ],
})
</script>

<template>
  <h1 class="text-2xl font-semibold p-4">Projets</h1>
</template>
