<template>
    <div class="bg-slate-50 min-h-screen pt-20"> <!-- pt-20 voor fixed navbar space -->
        
        <!-- Page Header -->
        <div class="bg-slate-900 py-16 text-center text-white relative overflow-hidden">
             <!-- Background pattern -->
            <div class="absolute inset-0 opacity-10 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')]"></div>
            <div class="relative z-10">
                <h1 class="text-4xl md:text-5xl font-extrabold mb-4">Contact</h1>
                <p class="text-slate-300 text-lg max-w-2xl mx-auto px-4">Wij horen graag van u. Vul het formulier in of bezoek ons op kantoor.</p>
            </div>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
            <div class="grid lg:grid-cols-3 gap-12">
                
                <!-- Contact Info Column -->
                <div class="lg:col-span-1 space-y-8">
                     <!-- Info Cards -->
                    <div class="bg-white p-8 rounded-xl shadow-sm border border-slate-100">
                        <h3 class="text-xl font-bold text-slate-900 mb-6">Contactgegevens</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="bg-blue-50 p-3 rounded-lg text-blue-600 mr-4">
                                     <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                                </div>
                                <div>
                                    <p class="font-bold text-slate-900">Bezoekadres</p>
                                    <p class="text-slate-600">Transportweg 12<br>3000 AB Rotterdam</p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                 <div class="bg-blue-50 p-3 rounded-lg text-blue-600 mr-4">
                                     <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C7.82 21 2 15.18 2 5V5z"></path></svg>
                                </div>
                                <div>
                                    <p class="font-bold text-slate-900">Telefoon</p>
                                    <a href="tel:+31101234567" class="text-blue-600 hover:underline">+31 (0)10 123 4567</a>
                                    <p class="text-xs text-slate-400 mt-1">Ma-Vr: 08:00 - 18:00</p>
                                </div>
                            </div>

                             <div class="flex items-start">
                                 <div class="bg-blue-50 p-3 rounded-lg text-blue-600 mr-4">
                                     <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v9a2 2 0 002 2z"></path></svg>
                                </div>
                                <div>
                                    <p class="font-bold text-slate-900">Email</p>
                                    <a href="mailto:info@transport-bedrijf.nl" class="text-blue-600 hover:underline">info@transport-bedrijf.nl</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Form Column -->
                <div class="lg:col-span-2">
                    <div class="bg-white rounded-xl shadow-lg border border-slate-100 p-8 md:p-10">
                        <h2 class="text-2xl font-bold text-slate-900 mb-6">Stuur ons een bericht</h2>
                        <form class="space-y-6">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 mb-2">Voornaam</label>
                                    <input type="text" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white" placeholder="Jan">
                                </div>
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 mb-2">Achternaam</label>
                                    <input type="text" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white" placeholder="Jansen">
                                </div>
                            </div>

                            <div>
                                <label class="block text-sm font-medium text-slate-700 mb-2">Bedrijfsnaam</label>
                                <input type="text" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white" placeholder="Optioneel">
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 mb-2">Email</label>
                                    <input type="email" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white" placeholder="jan@voorbeeld.nl">
                                </div>
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 mb-2">Telefoonnummer</label>
                                    <input type="tel" class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white" placeholder="06 12345678">
                                </div>
                            </div>

                            <div>
                                <label class="block text-sm font-medium text-slate-700 mb-2">Onderwerp</label>
                                <select class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white text-slate-600">
                                    <option>Offerte aanvraag</option>
                                    <option>Sollicitatie</option>
                                    <option>Algemene vraag</option>
                                    <option>Partnership</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-sm font-medium text-slate-700 mb-2">Uw bericht</label>
                                <textarea class="w-full px-4 py-3 rounded-lg border border-slate-200 focus:ring-2 focus:ring-blue-500 focus:border-blue-500 outline-none transition bg-slate-50 focus:bg-white h-40 resize-none" placeholder="Omschrijf uw vraag of opdracht..."></textarea>
                            </div>

                            <div class="flex items-center">
                                <input id="terms" type="checkbox" class="h-4 w-4 text-blue-600 focus:ring-blue-500 border-gray-300 rounded">
                                <label for="terms" class="ml-2 block text-sm text-slate-600">
                                    Ik ga akkoord met de <a href="#" class="text-blue-600 hover:underline">privacyverklaring</a>.
                                </label>
                            </div>

                            <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 rounded-lg transition shadow-lg transform hover:-translate-y-0.5">
                                Verstuur Bericht
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Map placeholder -->
        <div class="h-96 w-full bg-slate-200 relative grayscale">
             <div class="absolute inset-0 flex items-center justify-center">
                 <p class="text-slate-500 font-medium">Google Maps Integratie</p>
             </div>
             <!-- In production: iframe src="..." -->
        </div>

    </div>
</template>
