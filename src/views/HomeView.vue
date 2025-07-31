<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Accueil - Portfolio Audrey Gaborit',
  meta: [
    { name: 'description', content: 'Bienvenue sur mon portfolio de développeuse web.' },
    { property: 'og:title', content: 'Accueil - Portfolio Audrey Gaborit' },
    { property: 'og:description', content: 'Bienvenue sur mon portfolio de développeuse web.' },
  ]
})
</script>

<template>
  <h1 class="text-2xl font-extrabold p-4">Home</h1>
</template>
