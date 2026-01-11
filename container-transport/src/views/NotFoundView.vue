<template>
    <div class="min-h-screen bg-slate-50 flex flex-col items-center justify-center text-center px-4">
        <h1 class="text-9xl font-black text-slate-200 mb-4">404</h1>
        <h2 class="text-3xl font-bold text-slate-900 mb-4">Lading niet gevonden</h2>
        <p class="text-slate-600 mb-8 max-w-md">De pagina die u zoekt is verplaatst, verwijderd of heeft nooit bestaan. We brengen u graag weer op de juiste route.</p>
        
        <RouterLink to="/" class="bg-blue-600 hover:bg-blue-700 text-white px-8 py-3 rounded-lg font-bold transition shadow-lg">
            Terug naar Home
        </RouterLink>
    </div>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
