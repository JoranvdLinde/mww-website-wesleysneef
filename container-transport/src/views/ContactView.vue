<template>
    <div class="bg-slate-50 min-h-screen"> 
        
        <!-- Page Header -->
        <div class="bg-slate-900 pt-32 pb-20 lg:pt-40 lg:pb-24 text-center text-white relative overflow-hidden">
             <!-- Background pattern -->
            <div class="absolute inset-0 opacity-10 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')]"></div>
            <div class="relative z-10 container mx-auto px-4" data-aos="fade-down">
                <span class="inline-block px-4 py-1.5 rounded-full bg-blue-500/20 border border-blue-500/30 text-blue-300 font-bold text-sm tracking-wide uppercase mb-4 backdrop-blur-sm">Contacteer ons</span>
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold mb-6 leading-tight">Laten we samen <br/><span class="text-blue-500">meters maken</span>.</h1>
                <p class="text-slate-300 text-lg md:text-xl max-w-2xl mx-auto leading-relaxed">Of u nu een eenmalige zending heeft of een complexe logistieke uitdaging: ons team staat klaar om u te helpen.</p>
            </div>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 lg:py-24">
            <div class="grid lg:grid-cols-3 gap-12 items-start">
                
                <!-- Contact Info Column -->
                <div class="lg:col-span-1 space-y-8" data-aos="fade-right">
                     <!-- Info Cards -->
                    <div class="bg-white p-8 rounded-2xl shadow-lg border border-slate-100 relative overflow-hidden group">
                        <!-- Decorative bg blob -->
                        <div class="absolute top-0 right-0 -mr-16 -mt-16 w-32 h-32 bg-blue-50 rounded-full blur-2xl group-hover:bg-blue-100 transition duration-700"></div>

                        <h3 class="text-2xl font-bold text-slate-900 mb-8 relative z-10">Contactgegevens</h3>
                        
                        <div class="space-y-8 relative z-10">
                            <!-- Address -->
                            <div class="flex items-start group/item">
                                <div class="bg-blue-50 p-3.5 rounded-xl text-blue-600 mr-5 group-hover/item:bg-blue-600 group-hover/item:text-white transition-colors duration-300 shadow-sm">
                                     <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                                </div>
                                <div>
                                    <p class="font-bold text-slate-900 text-lg mb-1">Bezoekadres</p>
                                    <p class="text-slate-600 leading-relaxed">Transportweg 12<br>3000 AB Rotterdam</p>
                                </div>
                            </div>

                            <!-- Phone -->
                            <div class="flex items-start group/item">
                                 <div class="bg-blue-50 p-3.5 rounded-xl text-blue-600 mr-5 group-hover/item:bg-blue-600 group-hover/item:text-white transition-colors duration-300 shadow-sm">
                                     <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C7.82 21 2 15.18 2 5V5z"></path></svg>
                                </div>
                                <div>
                                    <p class="font-bold text-slate-900 text-lg mb-1">Telefoon & 24/7</p>
                                    <a href="tel:+31101234567" class="text-blue-600 font-medium hover:text-blue-800 transition block">+31 (0)10 123 4567</a>
                                    <p class="text-sm text-slate-400 mt-1">Noodgevallen: 24/7 bereikbaar</p>
                                </div>
                            </div>

                             <!-- Email -->
                             <div class="flex items-start group/item">
                                 <div class="bg-blue-50 p-3.5 rounded-xl text-blue-600 mr-5 group-hover/item:bg-blue-600 group-hover/item:text-white transition-colors duration-300 shadow-sm">
                                     <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v9a2 2 0 002 2z"></path></svg>
                                </div>
                                <div>
                                    <p class="font-bold text-slate-900 text-lg mb-1">Email</p>
                                    <a href="mailto:info@transport-bedrijf.nl" class="text-blue-600 font-medium hover:text-blue-800 transition break-all">info@transport-bedrijf.nl</a>
                                    <p class="text-sm text-slate-400 mt-1">Antwoord binnen 2 uur</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- KVK / BTW info card small -->
                     <div class="bg-slate-900 p-6 rounded-2xl shadow-lg border border-slate-800 text-slate-400 text-sm">
                         <div class="flex justify-between mb-2">
                             <span>KVK nummer:</span>
                             <span class="text-white font-mono">12345678</span>
                         </div>
                         <div class="flex justify-between">
                             <span>BTW nummer:</span>
                             <span class="text-white font-mono">NL123456789B01</span>
                         </div>
                     </div>
                </div>

                <!-- Form Column -->
                <div class="lg:col-span-2" data-aos="fade-left">
                    <div class="bg-white rounded-2xl shadow-xl border border-slate-100 p-8 md:p-12 relative overflow-hidden">
                         <div class="absolute top-0 right-0 w-24 h-24 bg-blue-600 -mr-12 -mt-12 rotate-45 transform"></div>

                        <h2 class="text-3xl font-extrabold text-slate-900 mb-2">Stuur een bericht</h2>
                        <p class="text-slate-600 mb-8">Vul onderstaand formulier in en wij nemen zo spoedig mogelijk contact met u op.</p>

                        <form class="space-y-6" @submit="handleSubmit">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">Voornaam</label>
                                    <input type="text" class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white placeholder-slate-400" placeholder="Bijv. Jan">
                                </div>
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">Achternaam</label>
                                    <input type="text" class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white placeholder-slate-400" placeholder="Bijv. Jansen">
                                </div>
                            </div>

                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-2">Bedrijfsnaam</label>
                                <input type="text" class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white placeholder-slate-400" placeholder="Uw organisatie (optioneel)">
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">Email</label>
                                    <input type="email" class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white placeholder-slate-400" placeholder="naam@bedrijf.nl">
                                </div>
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">Telefoonnummer</label>
                                    <input type="tel" class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white placeholder-slate-400" placeholder="06 12345678">
                                </div>
                            </div>

                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-2">Betreft</label>
                                <div class="relative">
                                    <select class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white text-slate-600 appearance-none cursor-pointer">
                                        <option>Offerte aanvraag</option>
                                        <option>Logistieke vraag</option>
                                        <option>Sollicitatie</option>
                                        <option>Samenwerking</option>
                                        <option>Anders</option>
                                    </select>
                                    <div class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-4 text-slate-500">
                                        <svg class="h-4 w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                                    </div>
                                </div>
                            </div>

                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-2">Uw bericht</label>
                                <textarea class="w-full px-4 py-3.5 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white h-40 resize-none placeholder-slate-400" placeholder="Hoe kunnen wij u helpen?"></textarea>
                            </div>

                            <div class="flex items-center">
                                <input id="terms" type="checkbox" class="h-4 w-4 text-blue-600 focus:ring-blue-500 border-gray-300 rounded cursor-pointer">
                                <label for="terms" class="ml-2 block text-sm text-slate-600 cursor-pointer select-none">
                                    Ik ga akkoord met de <a href="#" class="text-blue-600 hover:text-blue-700 underline font-medium">privacyverklaring</a>.
                                </label>
                            </div>

                            <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 rounded-xl transition-all shadow-lg hover:shadow-blue-500/30 transform hover:-translate-y-0.5 disabled:opacity-70 disabled:cursor-not-allowed disabled:transform-none" :disabled="isSubmitting">
                                <span v-if="!isSubmitting" class="flex items-center justify-center">
                                    Verstuur Bericht
                                    <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                                </span>
                                <span v-else class="flex items-center justify-center">
                                    <svg class="animate-spin -ml-1 mr-3 h-5 w-5 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"><circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle><path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path></svg>
                                    Verzenden...
                                </span>
                            </button>
                            <div v-if="formStatus === 'success'" class="mt-4 p-4 bg-green-50 border border-green-200 text-green-700 rounded-lg flex items-center animate-[fadeIn_0.5s_ease-out]">
                                <svg class="w-5 h-5 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span>Bedankt! Uw bericht is succesvol verzonden. We nemen z.s.m. contact op.</span>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>

        <!-- FAQ Section -->
        <section class="py-20 bg-white border-t border-slate-100">
             <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                 <div class="text-center mb-12">
                     <h2 class="text-3xl font-bold text-slate-900 mb-4">Veelgestelde vragen</h2>
                     <p class="text-slate-600">Wellicht staat uw antwoord hier al tussen.</p>
                 </div>
                 
                 <div class="space-y-4">
                     <!-- FAQ Item 1 -->
                     <details class="group bg-slate-50 p-6 rounded-xl cursor-pointer [&_summary::-webkit-details-marker]:hidden open:bg-white open:shadow-md open:ring-1 open:ring-black/5 transition-all">
                         <summary class="flex items-center justify-between font-bold text-slate-900 list-none">
                             Wat is de gemiddelde levertijd?
                             <span class="transition group-open:rotate-180">
                                 <svg fill="none" height="24" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" viewBox="0 0 24 24" width="24"><path d="M6 9l6 6 6-6"></path></svg>
                             </span>
                         </summary>
                         <p class="text-slate-600 mt-4 leading-relaxed text-sm md:text-base">
                             Binnen de Benelux leveren wij doorgaans binnen 24 uur. Voor internationale ritten is dit afhankelijk van de bestemming, maar wij streven altijd naar de snelst mogelijke route.
                         </p>
                     </details>

                      <!-- FAQ Item 2 -->
                     <details class="group bg-slate-50 p-6 rounded-xl cursor-pointer [&_summary::-webkit-details-marker]:hidden open:bg-white open:shadow-md open:ring-1 open:ring-black/5 transition-all">
                         <summary class="flex items-center justify-between font-bold text-slate-900 list-none">
                             Vervoeren jullie ook ADR (gevaarlijke goederen)?
                             <span class="transition group-open:rotate-180">
                                 <svg fill="none" height="24" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" viewBox="0 0 24 24" width="24"><path d="M6 9l6 6 6-6"></path></svg>
                             </span>
                         </summary>
                         <p class="text-slate-600 mt-4 leading-relaxed text-sm md:text-base">
                             Ja, een groot deel van onze vloot en chauffeurs is ADR-gecertificeerd. Neem contact op voor specifieke klassen en mogelijkheden.
                         </p>
                     </details>

                      <!-- FAQ Item 3 -->
                     <details class="group bg-slate-50 p-6 rounded-xl cursor-pointer [&_summary::-webkit-details-marker]:hidden open:bg-white open:shadow-md open:ring-1 open:ring-black/5 transition-all">
                         <summary class="flex items-center justify-between font-bold text-slate-900 list-none">
                             Kan ik een zending live volgen?
                             <span class="transition group-open:rotate-180">
                                 <svg fill="none" height="24" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" viewBox="0 0 24 24" width="24"><path d="M6 9l6 6 6-6"></path></svg>
                             </span>
                         </summary>
                         <p class="text-slate-600 mt-4 leading-relaxed text-sm md:text-base">
                             Zeker. Al onze trailers zijn uitgerust met GPS. Op aanvraag krijgt u toegang tot ons klantenportaal voor realtime updates.
                         </p>
                     </details>
                 </div>
             </div>
        </section>
        
        <!-- Map placeholder / Visual Break -->
        <div class="h-[500px] w-full bg-slate-200 relative grayscale filter contrast-[0.9]">
             <!-- Simulated Map UI -->
             <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1524661135-423995f22d0b?q=80&w=1748&auto=format&fit=crop')] bg-cover bg-center opacity-50"></div>
             
             <!-- Pin -->
             <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
                 <div class="relative">
                    <div class="w-4 h-4 bg-blue-600 rounded-full animate-ping absolute top-0 left-0"></div>
                    <div class="w-12 h-12 bg-blue-600 rounded-full border-4 border-white shadow-2xl flex items-center justify-center relative z-10">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path></svg>
                    </div>
                    <div class="absolute top-16 left-1/2 transform -translate-x-1/2 bg-white px-4 py-2 rounded-lg shadow-lg whitespace-nowrap font-bold text-slate-800 text-sm arrow-top">
                        Hoofdkwartier Rotterdam
                    </div>
                 </div>
             </div>
        </div>

    </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const isSubmitting = ref(false)
const formStatus = ref<'idle' | 'success' | 'error'>('idle')

const handleSubmit = async (e: Event) => {
    e.preventDefault()
    isSubmitting.value = true
    
    // Simulate API call
    await new Promise(resolve => setTimeout(resolve, 1500))
    
    isSubmitting.value = false
    formStatus.value = 'success'
    
    // Reset after 5 seconds
    setTimeout(() => {
        formStatus.value = 'idle'
    }, 5000)
}
</script>

<style scoped>
/* Custom caret for the map popup */
.arrow-top::before {
    content: "";
    position: absolute;
    bottom: 100%;
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: transparent transparent white transparent;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
}
</style>
