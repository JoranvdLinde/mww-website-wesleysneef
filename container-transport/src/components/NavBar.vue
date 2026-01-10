<script setup lang="ts">
import { RouterLink } from 'vue-router'
import { ref, onMounted, onUnmounted } from 'vue'

const isScrolled = ref(false)
const isMobileMenuOpen = ref(false)

const handleScroll = () => {
  isScrolled.value = window.scrollY > 20
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>

<template>
  <nav 
    class="fixed w-full z-50 transition-all duration-300"
    :class="[isScrolled ? 'bg-white/95 backdrop-blur-md shadow-sm py-2' : 'bg-transparent py-6']"
  >
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-16">
        <!-- Logo -->
        <div class="flex-shrink-0 flex items-center">
          <RouterLink to="/" class="group flex items-center gap-2">
            <div class="bg-blue-600 text-white p-2 rounded-lg group-hover:bg-blue-700 transition">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-6 h-6">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 18.75a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h6m-9 0H3.375a1.125 1.125 0 0 1-1.125-1.125V14.25m17.25 4.5a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h1.125c.621 0 1.129-.504 1.09-1.124a17.902 17.902 0 0 0-3.213-9.193 2.056 2.056 0 0 0-1.58-.86H14.25M16.5 18.75h-2.25m0-11.177v-.958c0-.568-.422-1.048-.987-1.106a48.554 48.554 0 0 0-10.026 0 1.106 1.106 0 0 0-.987 1.106v7.635m12-6.677v6.677m0 4.5v-4.5m0 0h-12" />
                </svg>
            </div>
            <span class="text-2xl font-bold uppercase tracking-tighter transition-colors"
               :class="[isScrolled ? 'text-slate-900' : 'text-white']">
               Trans<span class="text-blue-500">Port</span>
            </span>
          </RouterLink>
        </div>

        <!-- Desktop Menu -->
        <div class="hidden md:flex items-center space-x-8">
            <template v-for="item in ['Diensten', 'Over ons', 'Wagenpark']" :key="item">
                <a href="#" class="font-medium text-sm transition-colors hover:text-blue-500"
                   :class="[isScrolled ? 'text-slate-600' : 'text-slate-200']">
                    {{ item }}
                </a>
            </template>
            <RouterLink to="/contact" 
                class="px-5 py-2.5 rounded-full font-semibold text-sm transition-all transform hover:scale-105 shadow-lg"
                :class="[isScrolled ? 'bg-blue-600 text-white hover:bg-blue-700' : 'bg-white text-blue-900 hover:bg-slate-100']">
                Contact
            </RouterLink>
        </div>

        <!-- Mobile Menu Button -->
        <div class="md:hidden flex items-center">
            <button @click="isMobileMenuOpen = !isMobileMenuOpen" class="text-slate-500 hover:text-slate-700 focus:outline-none">
                <svg class="h-6 w-6" :class="[isScrolled ? 'text-slate-900' : 'text-white']" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path v-if="!isMobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
            </button>
        </div>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div v-show="isMobileMenuOpen" class="md:hidden bg-white border-t border-slate-100 shadow-xl">
        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
             <template v-for="item in ['Diensten', 'Over ons', 'Wagenpark']" :key="item">
                <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-slate-700 hover:text-blue-600 hover:bg-slate-50">
                    {{ item }}
                </a>
            </template>
            <RouterLink to="/contact" class="block w-full text-center mt-4 px-3 py-3 rounded-md text-base font-bold bg-blue-600 text-white hover:bg-blue-700">
                Neem Contact Op
            </RouterLink>
        </div>
    </div>
  </nav>
</template>
