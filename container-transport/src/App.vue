<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<template>
  <div class="min-h-screen bg-slate-50 font-sans text-slate-900 flex flex-col">
    <NavBar />

    <main class="flex-grow">
        <RouterView />
    </main>

    <AppFooter />
  </div>
</template>

<style>
/* Global styling if needed */
html {
    scroll-behavior: smooth;
}
</style>
