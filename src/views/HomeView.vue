<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Accueil - Portfolio Audrey Gaborit',
  meta: [
    { name: 'description', content: 'Bienvenue sur mon portfolio de développeuse web.' },
    { property: 'og:title', content: 'Accueil - Portfolio Audrey Gaborit' },
    { property: 'og:description', content: 'Bienvenue sur mon portfolio de développeuse web.' },
  ],
})
</script>

<template>
  <section class="w-full flex flex-col items-center pt-8 px-4 gap-2 md:gap-0">
    <p class="text-lg md:text-xl lg:text-3xl font-bold text-primary italic pt-10">
      Salut ! Je suis Audrey
    </p>
    <h1
      class="bg-gradient-to-r from-[#416146] to-[#A0DEA6] bg-clip-text text-4xl md:text-8xl lg:text-[140px] font-extrabold text-transparent"
    >
      Développeuse
    </h1>
    <div
      class="w-full flex justify-between bg-gradient-to-r from-[#416146] to-[#A0DEA6] bg-clip-text text-2xl md:text-6xl lg:text-8xl font-extrabold text-transparent"
    >
      <span>Frontend</span> <span>Backend</span>
    </div>
    <div class="relative md:static w-full flex flex-1 justify-center">
      <img
        src="@/assets/avatar.png"
        alt="Avatar"
        class="absolute z-1 bottom-0 lg:h-[65%] filter brightness-130 object-contain w-50 lg:w-100"
      />
    </div>
  </section>
</template>
