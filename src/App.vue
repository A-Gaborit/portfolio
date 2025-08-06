<script setup lang="ts">
import { RouterView } from 'vue-router'

import HeaderBar from './components/HeaderBar.vue'
import FooterBar from './components/FooterBar.vue'
</script>

<template>
  <HeaderBar />
  <main class="flex-1 flex flex-col w-full min-h-0">
    <router-view />
  </main>
  <FooterBar />
</template>
