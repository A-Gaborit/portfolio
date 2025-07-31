<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <header class="bg-white shadow">
    <nav class="flex items-center justify-between p-4">
      <RouterLink class="font-extrabold text-xl" to="/">Audrey Gaborit</RouterLink>
      <div class="flex gap-6">
        <RouterLink to="/">Accueil</RouterLink>
        <RouterLink to="/career">Parcours</RouterLink>
        <RouterLink to="/skills">Compétences</RouterLink>
        <RouterLink to="/projects">Projets</RouterLink>
        <RouterLink to="/contact">Contact</RouterLink>
      </div>
    </nav>
  </header>
  <div class="flex justify-center">
    <RouterView/>
  </div>
  <main class="flex flex-col items-center justify-center min-h-[80vh] bg-white">
    <svg width="64" height="64" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="mb-4">
      <path d="M7 17h10M8.5 13l1.5-6h4l1.5 6" stroke="#af0000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
    <h1 class="text-2xl font-extrabold text-red-800 mb-2">Site en cours de construction</h1>
    <p class="text-gray-600">Merci de votre visite ! Ce portfolio sera bientôt disponible.</p>
  </main>
</template>

<style scoped>

</style>
