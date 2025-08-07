<script setup lang="ts">
import { ref } from 'vue'
import { RouterLink } from 'vue-router'

const mobileMenuOpen = ref(false)
</script>

<template>
  <header class="w-full">
    <nav
      class="flex w-full items-center justify-between rounded-xl border border-white bg-white/50 px-6 py-2 shadow-lg backdrop-blur-xl dark:bg-black/20 dark:border-black/20"
    >
      <span class="text-xl lg:text-3xl font-bold text-black-soft pattaya">Audrey Gaborit</span>
      <!-- Desktop menu -->
      <div class="relative gap-4 text-md lg:text-lg hidden sm:flex">
        <RouterLink class="text-black-soft font-bold" to="/">ACCUEIL</RouterLink>
        <RouterLink class="text-black-soft font-bold" to="/career">PARCOURS</RouterLink>
        <RouterLink class="text-black-soft font-bold" to="/skills">COMPÉTENCES</RouterLink>
        <RouterLink class="text-black-soft font-bold" to="/projects">PROJETS</RouterLink>
        <RouterLink class="text-black-soft font-bold" to="/contact">CONTACT</RouterLink>
      </div>
      <!-- Hamburger for mobile -->
      <button
        class="sm:hidden flex items-center justify-center text-black-soft text-3xl focus:outline-none"
        @click="mobileMenuOpen = true"
      >
        <span class="material-symbols-outlined">menu</span>
      </button>
    </nav>
    <!-- Mobile fullscreen menu -->
    <div
      v-if="mobileMenuOpen"
      class="fixed inset-0 z-50 flex flex-col items-center justify-center bg-white/30 backdrop-blur-2xl"
    >
      <button
        class="absolute top-6 right-6 text-4xl text-black-soft"
        @click="mobileMenuOpen = false"
      >
        <span class="material-symbols-outlined">close</span>
      </button>
      <nav class="flex flex-col items-center gap-6 text-2xl font-bold">
        <RouterLink class="text-black-soft" to="/" @click="mobileMenuOpen = false"
          >ACCUEIL</RouterLink
        >
        <RouterLink class="text-black-soft" to="/career" @click="mobileMenuOpen = false"
          >PARCOURS</RouterLink
        >
        <RouterLink class="text-black-soft" to="/skills" @click="mobileMenuOpen = false"
          >COMPÉTENCES</RouterLink
        >
        <RouterLink class="text-black-soft" to="/projects" @click="mobileMenuOpen = false"
          >PROJETS</RouterLink
        >
        <RouterLink class="text-black-soft" to="/contact" @click="mobileMenuOpen = false"
          >CONTACT</RouterLink
        >
      </nav>
    </div>
  </header>
</template>
