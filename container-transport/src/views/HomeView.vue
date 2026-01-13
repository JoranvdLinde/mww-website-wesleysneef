<template>
  <div>
    <!-- Hero Section -->
    <header class="relative min-h-screen flex items-center justify-center bg-slate-900 text-white overflow-hidden">
        <!-- Abstract Background -->
        <div class="absolute inset-0 z-0 opacity-40 bg-[url('https://images.unsplash.com/photo-1577149004697-96e1e216ad92?q=80&w=2070&auto=format&fit=crop')] bg-cover bg-center"></div>
        <div class="absolute inset-0 bg-gradient-to-b from-slate-900/80 via-slate-900/60 to-slate-50 z-0"></div> <!-- Gradient naar wit onderaan voor smooth transition -->

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center pt-20">
            <div data-aos="fade-down" class="mb-6 inline-flex items-center gap-2 px-4 py-2 rounded-full bg-blue-600/20 border border-blue-500/30 backdrop-blur-sm">
                <span class="flex h-2 w-2 relative">
                    <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-blue-400 opacity-75"></span>
                    <span class="relative inline-flex rounded-full h-2 w-2 bg-blue-500"></span>
                </span>
                <span class="text-blue-200 text-sm font-medium uppercase tracking-wider">Nu beschikbaar voor nieuwe opdrachten</span>
            </div>
            <h1 data-aos="fade-up" data-aos-delay="100" class="text-4xl sm:text-5xl md:text-7xl lg:text-8xl font-black tracking-tight mb-8 leading-tight">
                Logistiek <br/> Zonder <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-indigo-500">Grenzen</span>
            </h1>
            <p data-aos="fade-up" data-aos-delay="200" class="text-xl md:text-2xl text-slate-300 mb-10 max-w-3xl mx-auto leading-relaxed font-light">
                Wij zijn de motor achter uw supply chain. <strong class="text-white font-semibold">Snel, veilig en efficiënt</strong> container transport door heel Europa.
            </p>
            <div data-aos="fade-up" data-aos-delay="300" class="flex flex-col sm:flex-row gap-5 justify-center">
                <RouterLink to="/contact" class="bg-blue-600 hover:bg-blue-500 text-white px-10 py-4 rounded-full font-bold text-lg transition-all transform hover:-translate-y-1 shadow-[0_10px_30px_-10px_rgba(37,99,235,0.5)]">
                    Vraag Offerte Aan
                </RouterLink>
                <a href="#services" class="bg-white/5 hover:bg-white/10 text-white border border-white/20 px-10 py-4 rounded-full font-bold text-lg transition backdrop-blur-md">
                    Ontdek Onze Kracht
                </a>
            </div>
        </div>
        
        <!-- Scroll indicator -->
        <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 animate-bounce opacity-50 hidden md:block">
            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path></svg>
        </div>
    </header>

    <!-- Services Grid -->
    <section id="services" class="py-32 bg-slate-50 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-20" data-aos="fade-up">
                <h2 class="text-4xl lg:text-5xl font-extrabold text-slate-900 mb-6 tracking-tight">Onze Expertise</h2>
                <p class="text-xl text-slate-600 max-w-2xl mx-auto leading-relaxed">Wij bieden meer dan alleen transport. Wij bieden totale ontzorging van uw logistieke proces.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-6 md:gap-10">
                <!-- Card 1 -->
                <div data-aos="fade-up" data-aos-delay="100" class="group bg-white p-6 md:p-10 rounded-2xl border border-slate-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2">
                    <div class="h-16 w-16 bg-blue-50 text-blue-600 rounded-2xl flex items-center justify-center mb-8 group-hover:bg-blue-600 group-hover:text-white transition-colors duration-300">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-slate-900">Sneltransport</h3>
                    <p class="text-slate-600 leading-relaxed mb-6">Tijd is geld. Voor spoedklussen staan wij 24/7 klaar met toegewijde chauffeurs die direct vertrekken.</p>
                    <a href="#" class="inline-flex items-center text-blue-600 font-semibold hover:text-blue-700">Lees meer <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg></a>
                </div>
                 <!-- Card 2 -->
                 <div data-aos="fade-up" data-aos-delay="200" class="group bg-white p-6 md:p-10 rounded-2xl border border-slate-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2">
                    <div class="h-16 w-16 bg-blue-50 text-blue-600 rounded-2xl flex items-center justify-center mb-8 group-hover:bg-blue-600 group-hover:text-white transition-colors duration-300">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z"></path></svg>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-slate-900">Container Handling</h3>
                    <p class="text-slate-600 leading-relaxed mb-6">Gespecialiseerd in 20ft, 40ft en High Cube containers. Inclusief veilige op- en overslag faciliteiten.</p>
                    <a href="#" class="inline-flex items-center text-blue-600 font-semibold hover:text-blue-700">Lees meer <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg></a>
                </div>
                 <!-- Card 3 -->
                 <div data-aos="fade-up" data-aos-delay="300" class="group bg-white p-6 md:p-10 rounded-2xl border border-slate-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2">
                    <div class="h-16 w-16 bg-blue-50 text-blue-600 rounded-2xl flex items-center justify-center mb-8 group-hover:bg-blue-600 group-hover:text-white transition-colors duration-300">
                         <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-slate-900">Internationaal</h3>
                    <p class="text-slate-600 leading-relaxed mb-6">Naadloos grensoverschrijdend transport. Wij regelen alle douanepapieren en vergunningen voor u.</p>
                    <a href="#" class="inline-flex items-center text-blue-600 font-semibold hover:text-blue-700">Lees meer <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Break / Parallax feel -->
    <section class="relative py-40 flex items-center bg-slate-900 overflow-hidden">
        <div class="absolute inset-0 z-0 bg-[url('/src/assets/vrachtwagen.png')] bg-cover bg-fixed bg-center opacity-40"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 w-full flex flex-col items-center">
            <h2 class="text-4xl font-bold text-white mb-6 text-center">Onderdeel van uw groei.</h2>
            <p class="text-xl text-slate-300 mb-8 leading-relaxed text-center">
                Terwijl u zich richt op uw core business, zorgen wij dat uw goederen veilig en op tijd aankomen. Van Rotterdam haven tot het diepste puntje van Duitsland.
            </p>
            <RouterLink to="/contact" class="inline-block bg-blue-600 hover:bg-blue-500 text-white px-8 py-3 rounded-md font-bold text-lg transition shadow-lg">
                Bekijk onze bestemmingen
            </RouterLink>
        </div>
    </section>

    <!-- Why Us Section (About) -->
    <section class="py-24 bg-white overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div data-aos="fade-right">
                    <div class="inline-block px-4 py-1.5 rounded-full bg-blue-100 text-blue-700 font-bold text-sm tracking-wide uppercase mb-6">Over TransPort</div>
                    <h2 class="text-4xl lg:text-5xl font-extrabold text-slate-900 mb-6 leading-tight">Uw lading is <br/>onze <span class="text-blue-600">toewijding</span>.</h2>
                    <p class="text-lg text-slate-600 mb-6 leading-relaxed">
                        TransPort is in 2010 opgericht met één missie: containervervoer simpeler, transparanter en betrouwbaarder maken. Waar anderen problemen zien, zien wij routes.
                    </p>
                    <p class="text-lg text-slate-600 mb-8 leading-relaxed">
                        Met een team van ervaren planners en chauffeurs zorgen wij ervoor dat uw goederen altijd op tijd zijn, ongeacht de uitdaging. Wij geloven in langdurige partnerschappen, niet in snelle ritjes.
                    </p>
                    
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-start">
                            <svg class="w-6 h-6 text-green-500 mr-3 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            <span class="text-slate-700 font-medium">Volledig digitaal track & trace systeem</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="w-6 h-6 text-green-500 mr-3 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            <span class="text-slate-700 font-medium">Eigen moderne vloot (Euro 6 norm)</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="w-6 h-6 text-green-500 mr-3 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            <span class="text-slate-700 font-medium">Persoonlijk contact met vaste planners</span>
                        </li>
                    </ul>

                    <RouterLink to="/contact" class="text-blue-600 font-bold hover:text-blue-800 transition flex items-center group">
                        Leer ons team kennen 
                        <svg class="w-5 h-5 ml-2 transform group-hover:translate-x-1 transition" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                    </RouterLink>
                </div>
                <div data-aos="fade-left" class="relative">
                     <div class="absolute -top-10 -right-10 w-72 h-72 bg-blue-100/50 rounded-full blur-3xl -z-10"></div>
                     <div class="absolute -bottom-10 -left-10 w-72 h-72 bg-indigo-100/50 rounded-full blur-3xl -z-10"></div>
                     <img src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?q=80&w=2070&auto=format&fit=crop" class="rounded-2xl shadow-2xl w-full h-auto object-cover" alt="Logistiek planner aan het werk">
                     
                     <!-- Floating Card -->
                     <div class="absolute bottom-8 left-8 bg-white p-6 rounded-xl shadow-xl max-w-xs hidden md:block animate-bounce" style="animation-duration: 3s;">
                        <div class="flex items-center gap-4">
                             <div class="bg-green-100 p-2 rounded-full text-green-600 px-3">
                                 <span class="font-bold">24/7</span>
                             </div>
                             <div>
                                 <p class="text-xs text-slate-500 uppercase font-bold">Live Support</p>
                                 <p class="font-bold text-slate-900">Altijd bereikbaar</p>
                             </div>
                        </div>
                     </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Fleet / Wagenpark Showcase -->
    <section class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
             <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div class="max-w-2xl" data-aos="fade-right">
                    <h2 class="text-3xl md:text-4xl font-extrabold text-slate-900 mb-4">Onze Krachtpatsers</h2>
                    <p class="text-lg text-slate-600">Een modern wagenpark is de basis van betrouwbaarheid. Wij investeren continu in de nieuwste technologie.</p>
                </div>
                <div data-aos="fade-left" class="mt-6 md:mt-0">
                    <a href="#" class="text-blue-600 font-bold hover:text-blue-800 transition">Bekijk alle specificaties &rarr;</a>
                </div>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Fleet Item 1 -->
                <div data-aos="fade-up" data-aos-delay="0" class="group relative overflow-hidden rounded-2xl shadow-lg h-96">
                    <img src="https://images.unsplash.com/photo-1601584115197-04ecc0da31d7?q=80&w=2070&auto=format&fit=crop" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="Truck">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 to-transparent flex flex-col justify-end p-8">
                        <h3 class="text-white font-bold text-2xl mb-1">DAF XG+</h3>
                        <p class="text-slate-300">Long Haul Specialist</p>
                    </div>
                </div>
                 <!-- Fleet Item 2 -->
                 <div data-aos="fade-up" data-aos-delay="100" class="group relative overflow-hidden rounded-2xl shadow-lg h-96">
                    <img src="https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?q=80&w=2070&auto=format&fit=crop" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="Truck Trailer">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 to-transparent flex flex-col justify-end p-8">
                        <h3 class="text-white font-bold text-2xl mb-1">Krone Container Chassis</h3>
                        <p class="text-slate-300">Multifunctioneel inzetbaar</p>
                    </div>
                </div>
                 <!-- Fleet Item 3 -->
                  <div data-aos="fade-up" data-aos-delay="200" class="group relative overflow-hidden rounded-2xl shadow-lg h-96 md:col-span-2 lg:col-span-1">
                    <img src="https://images.unsplash.com/photo-1577149004697-96e1e216ad92?q=80&w=2070&auto=format&fit=crop" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="Haven Logistics">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 to-transparent flex flex-col justify-end p-8">
                        <h3 class="text-white font-bold text-2xl mb-1">Haven Logistics</h3>
                        <p class="text-slate-300">Directe aansluiting</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-blue-600 py-12 md:py-20 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div data-aos="zoom-in" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-8 text-center bg-blue-700/20 rounded-2xl p-8 backdrop-blur-sm border border-blue-400/20">
                <div class="p-4">
                    <div class="text-4xl md:text-5xl font-black mb-2">15<span class="text-blue-200 text-3xl">+</span></div>
                    <div class="text-blue-100 font-medium tracking-wide">Jaren Ervaring</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl md:text-5xl font-black mb-2">50<span class="text-blue-200 text-3xl">+</span></div>
                    <div class="text-blue-100 font-medium tracking-wide">Vrachtwagens</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl md:text-5xl font-black mb-2">12<span class="text-blue-200 text-3xl">k</span></div>
                    <div class="text-blue-100 font-medium tracking-wide">Containers/Jaar</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl md:text-5xl font-black mb-2">100<span class="text-blue-200 text-3xl">%</span></div>
                    <div class="text-blue-100 font-medium tracking-wide">Tevredenheid</div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-24 bg-white">
        <div data-aos="fade-up" class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-4xl font-bold text-slate-900 mb-6">Klaar om te schakelen?</h2>
            <p class="text-xl text-slate-600 mb-10 max-w-2xl mx-auto">
                Neem vandaag nog contact op voor een vrijblijvende offerte of adviesgesprek. Onze planners zitten klaar.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <RouterLink to="/contact" class="bg-slate-900 hover:bg-slate-800 text-white px-10 py-4 rounded-lg font-bold text-lg transition shadow-xl">
                    Direct Contact Opnemen
                </RouterLink>
                 <a href="tel:0101234567" class="flex items-center justify-center text-slate-700 bg-slate-100 hover:bg-slate-200 px-10 py-4 rounded-lg font-bold text-lg transition border border-slate-200">
                    <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C7.82 21 2 15.18 2 5V5z"></path></svg>
                    Bel 010 - 123 4567
                </a>
            </div>
        </div>
    </section>
  </div>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
