<script setup lang="ts">
import { RouterView } from 'vue-router'

import HeaderBar from './components/HeaderBar.vue'
import FooterBar from './components/FooterBar.vue'
</script>

<template>
  <HeaderBar />
  <main class="w-full flex flex-1 justify-center">
    <router-view />
  </main>
  <FooterBar />
</template>
