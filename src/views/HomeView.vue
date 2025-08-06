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
  <section class="flex-1 min-h-0 flex flex-col items-center pt-8 px-4 w-full">
    <p class="text-lg md:text-2xl lg:text-3xl xl:text-4xl font-bold text-primary italic pt-10">
      Salut ! Je suis Audrey
    </p>
    <h1
      class="bg-gradient-to-r from-[#416146] to-[#A0DEA6] bg-clip-text text-[42px] md:text-8xl lg:text-[140px] font-extrabold text-transparent"
    >
      Développeuse
    </h1>
    <div
      class="w-full flex justify-between bg-gradient-to-r from-[#416146] to-[#A0DEA6] bg-clip-text font-extrabold text-transparent"
    >
      <h2 class="text-[28px] md:text-6xl lg:text-7xl xl:text-8xl">Frontend</h2>
      <h2 class="text-[28px] md:text-6xl lg:text-7xl xl:text-8xl">Backend</h2>
    </div>
    <div class="flex flex-1 min-h-0 justify-center items-end min-w-0">
      <img
        src="@/assets/avatar.png"
        alt="Avatar"
        class="filter brightness-130 object-contain flex flex-1 max-h-full h-auto md:h-full lg:scale-[110%] lg:translate-y-[-5%]"
      />
    </div>
  </section>
</template>
