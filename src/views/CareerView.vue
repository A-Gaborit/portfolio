<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Parcours - Portfolio Audrey Gaborit',
  meta: [
    { name: 'description', content: 'Découvrez mon parcours professionnel et mes expériences.' },
    { property: 'og:title', content: 'Parcours - Portfolio Audrey Gaborit' },
    { property: 'og:description', content: 'Découvrez mon parcours professionnel et mes expériences.' },
  ]
})
</script>

<template>
  <h1 class="text-2xl font-extrabold p-4">Parcours</h1>
</template>
