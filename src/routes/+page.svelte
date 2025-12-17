<script lang="ts">
    import AppButtons from "$lib/components/AppButtons.svelte";
    import PhoneMockup from "$lib/components/PhoneMockup.svelte";
</script>

<div class="w-full overflow-hidden">
    <!-- Header -->
    <header class="w-full py-8 flex flex-col items-center justify-center text-center">
        <h1 class="text-4xl font-serif font-medium tracking-tight">Sixteen.</h1>
        <p class="text-xs uppercase tracking-widest text-gray-500 mt-2 font-sans">New York's #1 Focus & Fitness App</p>
    </header>

    <!-- Hero Section -->
    <section class="max-w-7xl mx-auto px-6 pt-12 pb-24 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
        <div class="flex flex-col items-start space-y-8">
            <h2 class="text-6xl md:text-7xl font-serif leading-[1.1]">
                Earn your<br/>
                screen time.
            </h2>
            <p class="text-gray-600 max-w-md leading-relaxed">
                Sixteen transforms phone addiction into physical discipline. Want to unlock Instagram? Do 20 pushups. Your distractions now cost movement, not just willpower.
            </p>
            <div class="pt-2">
                <AppButtons />
            </div>
        </div>
        
        <div class="relative flex justify-center items-center">
            <!-- Abstract Background Shapes -->
            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] opacity-50 pointer-events-none">
                 <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" class="w-full h-full fill-[#F2EBE0]">
                    <path d="M44.7,-76.4C58.9,-69.2,71.8,-59.1,81.6,-46.6C91.4,-34.1,98.2,-19.2,95.8,-5.2C93.4,8.8,81.8,21.9,71.2,33.7C60.6,45.4,51,55.8,39.9,64.4C28.8,73,16.2,79.8,2.6,75.3C-11,70.8,-25.6,55,-38.7,42.5C-51.8,30,-63.4,20.8,-69.3,8.7C-75.2,-3.4,-75.4,-18.4,-68.8,-31.6C-62.2,-44.8,-48.8,-56.2,-35.4,-63.8C-22,-71.4,-8.6,-75.2,5.2,-84.2C19,-93.2,30.5,-107.4,44.7,-76.4Z" transform="translate(100 100)" />
                  </svg>
            </div>
            
            <PhoneMockup>
                <!-- Mockup Content -->
                <div class="flex flex-col h-full p-6 items-center pt-16 justify-center">
                    <div class="w-20 h-20 bg-red-100 rounded-2xl flex items-center justify-center mb-6">
                        <span class="text-4xl">📱</span>
                    </div>
                    <h3 class="text-2xl font-serif text-center mb-2">Instagram is locked</h3>
                    <p class="text-sm text-gray-500 text-center mb-8">Do 20 pushups to unlock</p>
                    <div class="w-full bg-gray-100 rounded-full h-3 mb-4">
                        <div class="bg-black h-3 rounded-full" style="width: 45%"></div>
                    </div>
                    <p class="text-xs text-gray-400">9 / 20 pushups</p>
                    <button class="bg-black text-white px-8 py-3 rounded-full w-full font-medium mt-auto mb-12">
                        Continue Exercise
                    </button>
                </div>
            </PhoneMockup>
        </div>
    </section>

    <!-- Dark Section (Principles) -->
    <section class="bg-[#1C1C1C] text-white py-24 overflow-hidden relative">
        <div class="max-w-7xl mx-auto px-6 mb-16">
            <p class="text-xl md:text-2xl font-serif max-w-lg leading-relaxed text-gray-300">
                Built by a rogue team designing software that fights back against digital junk.
            </p>
        </div>

        <div class="relative w-full overflow-x-hidden">
            <div class="flex whitespace-nowrap px-6 gap-4 md:gap-12 items-center">
                 <!-- Item 1 -->
                 <div class="inline-flex items-baseline">
                    <span class="text-[120px] md:text-[180px] font-serif font-light text-transparent stroke-text opacity-50" style="-webkit-text-stroke: 1px rgba(255,255,255,0.5);">1.</span>
                    <div class="flex flex-col ml-4">
                        <span class="text-5xl md:text-7xl font-serif">Friction,</span>
                        <span class="text-5xl md:text-7xl font-serif font-bold">not force.</span>
                    </div>
                 </div>
                 
                 <!-- Item 2 -->
                 <div class="inline-flex items-baseline ml-12 md:ml-24">
                    <span class="text-[120px] md:text-[180px] font-serif font-light text-[#E6D8C0]">2.</span>
                    <div class="flex flex-col ml-4">
                        <span class="text-5xl md:text-7xl font-serif">Movement,</span>
                        <span class="text-5xl md:text-7xl font-serif font-bold">not shame.</span>
                    </div>
                 </div>

                 <!-- Hint of Item 3 -->
                   <div class="inline-flex items-baseline ml-12 md:ml-24 opacity-20">
                    <span class="text-[120px] md:text-[180px] font-serif font-light">3.</span>
                 </div>
            </div>
        </div>

        <div class="max-w-7xl mx-auto px-6 mt-12 flex justify-end">
            <div class="flex gap-2">
                <div class="w-3 h-3 rounded-full bg-white"></div>
                <div class="w-3 h-3 rounded-full bg-gray-600"></div>
            </div>
        </div>
    </section>

    <!-- Why we're different -->
    <section class="py-32 max-w-5xl mx-auto px-6">
        <div class="text-center mb-24">
            <p class="text-sm uppercase tracking-widest text-gray-500">Why we're different</p>
        </div>

        <div class="space-y-32">
            <!-- Feature 1 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Friction-based<br>design, not<br>blocking</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        We don't block your apps. We make you earn them. Every unlock requires physical movement, creating mindful friction instead of guilt-based restrictions.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Exercise -->
                    <div class="w-64 h-64 relative">
                        <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <circle cx="100" cy="60" r="20" />
                            <path d="M100,80 L100,130" />
                            <path d="M70,100 L130,100" />
                            <path d="M100,130 L80,170" />
                            <path d="M100,130 L120,170" />
                        </svg>
                        <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-[#F2EBE0] rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>

            <!-- Feature 2 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Screen Time<br>Bank saves<br>your progress</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Earned time doesn't disappear. Bank up to 1 hour of screen time for later use. Your discipline today becomes freedom tomorrow.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Bank/Savings -->
                    <div class="w-64 h-64 relative">
                        <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <rect x="50" y="80" width="100" height="80" rx="10" />
                            <path d="M70,100 L130,100" />
                            <path d="M70,120 L130,120" />
                            <path d="M70,140 L130,140" />
                            <circle cx="100" cy="60" r="15" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-[#F2EBE0] rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>

            <!-- Feature 3 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Emergency<br>Keys for<br>real life</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Life happens. Get 2 emergency unlocks per week, each giving you 1 hour of app access. No exercise required, no shame attached.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Key -->
                    <div class="w-64 h-64 relative">
                        <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <circle cx="60" cy="100" r="25" />
                            <circle cx="60" cy="100" r="12" />
                            <path d="M85,100 L140,100" />
                            <path d="M120,90 L120,100" />
                            <path d="M130,90 L130,100" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-[#F2EBE0] rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>
            
             <!-- Feature 4 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Reflection<br>Questions<br>create pauses</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Before unlocking apps, we ask why you want to open them. These mindful pauses help you reclaim intention, not just time.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Question Mark -->
                    <div class="w-64 h-64 relative">
                         <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <path d="M80,70 Q80,50 100,50 Q120,50 120,70 Q120,85 100,90 L100,110" />
                            <circle cx="100" cy="130" r="5" fill="black" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-[#F2EBE0] rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>

             <!-- Feature 5 -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center group">
                <div>
                    <h3 class="text-5xl md:text-6xl font-serif mb-6 group-hover:italic transition-all duration-300">Apple Watch<br>integration<br>coming soon</h3>
                    <p class="text-gray-600 max-w-xs text-sm leading-relaxed">
                        Automatic rep counting for pushups, squats, and planks. No more manual input—just move and unlock.
                    </p>
                    <div class="mt-4 text-xs text-gray-400">→</div>
                </div>
                <div class="flex justify-center">
                    <!-- Illustration Placeholder: Watch -->
                    <div class="w-64 h-64 relative">
                         <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                            <rect x="70" y="80" width="60" height="40" rx="8" />
                            <path d="M70,70 L70,80 L130,80 L130,70" />
                            <path d="M70,120 L70,130 L130,130 L130,120" />
                            <circle cx="100" cy="100" r="8" fill="black" />
                        </svg>
                         <div class="absolute -z-10 top-10 right-10 w-40 h-40 bg-[#F2EBE0] rounded-full opacity-50 blur-xl"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Mid CTA -->
    <section class="py-24 bg-[#FCFAF7] border-y border-gray-100">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div>
                <p class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
                    Reclaim hours you didn't realize you were losing. Transform compulsive phone checking into physical strength and mental clarity.
                </p>
                <AppButtons />
            </div>
            <div class="flex justify-center">
                <!-- Phone + Dumbbell Illustration -->
                 <div class="w-64 h-64 relative">
                     <svg viewBox="0 0 200 200" class="w-full h-full stroke-black fill-none stroke-[1.5]">
                        <rect x="70" y="40" width="60" height="100" rx="8" />
                        <circle cx="100" cy="30" r="3" fill="black" />
                        <path d="M40,160 L160,160" stroke-width="3" />
                        <circle cx="40" cy="160" r="12" />
                        <circle cx="160" cy="160" r="12" />
                    </svg>
                    <div class="absolute -z-10 bottom-0 left-10 w-40 h-20 bg-[#E6D8C0] rounded-full opacity-50 blur-xl"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Dark Cards Section -->
    <section class="py-24">
        <div class="max-w-4xl mx-auto px-6 mb-16">
            <h2 class="text-4xl font-serif">Sixteen rewires your daily<br>routines, not just blocks apps.</h2>
            <p class="text-gray-500 mt-4 max-w-md">
                Built for people who work online but want to stay human. Master your technology, don't quit it.
            </p>
        </div>

        <div class="max-w-6xl mx-auto px-6 space-y-8">
            <!-- Card 1 -->
            <div class="bg-[#1C1C1C] rounded-[2rem] p-12 md:p-20 text-white relative overflow-hidden flex flex-col md:flex-row items-center gap-12">
                <div class="relative z-10 w-full md:w-1/2 flex justify-center">
                     <PhoneMockup>
                         <div class="p-6 flex flex-col h-full bg-white text-black justify-center items-center">
                             <div class="w-24 h-24 bg-black rounded-2xl flex items-center justify-center mb-6">
                                 <span class="text-5xl">💪</span>
                             </div>
                             <h4 class="text-2xl font-serif text-center mb-2">TikTok</h4>
                             <p class="text-sm text-gray-500 text-center mb-6">Locked until 8:00 PM</p>
                             <div class="w-full bg-gray-100 rounded-full h-2">
                                 <div class="bg-black h-2 rounded-full" style="width: 0%"></div>
                             </div>
                             <p class="text-xs text-gray-400 mt-2">0 / 30 squats to unlock</p>
                         </div>
                     </PhoneMockup>
                </div>
                <div class="w-full md:w-1/2 relative z-10">
                    <p class="text-xs uppercase tracking-widest text-gray-400 mb-2">Exercise to unlock</p>
                    <h3 class="text-4xl md:text-5xl font-serif mb-6">Your distractions<br>cost movement</h3>
                    <p class="text-gray-400 leading-relaxed">
                        Choose which apps require exercise to unlock. Set custom rep counts. Every time you reach for distraction, you build physical strength instead.
                    </p>
                </div>
                <!-- Abstract BG -->
                <div class="absolute left-0 bottom-0 w-1/2 h-full bg-white opacity-5 rounded-full blur-3xl translate-y-1/2 -translate-x-1/4"></div>
            </div>

             <!-- Card 2 -->
            <div class="bg-[#1C1C1C] rounded-[2rem] p-12 md:p-20 text-white relative overflow-hidden flex flex-col md:flex-row-reverse items-center gap-12">
                <div class="relative z-10 w-full md:w-1/2 flex justify-center">
                     <PhoneMockup>
                         <div class="p-6 flex flex-col h-full bg-white text-black">
                             <div class="text-xs text-gray-500 uppercase tracking-widest mb-4">Screen Time Bank</div>
                             <div class="bg-gray-50 rounded-xl p-6 mb-4">
                                 <h4 class="text-3xl font-serif mb-2">47 min</h4>
                                 <p class="text-sm text-gray-500">Saved for later</p>
                             </div>
                             <div class="space-y-2">
                                 <div class="flex justify-between text-sm">
                                     <span class="text-gray-500">Today earned</span>
                                     <span class="font-medium">+23 min</span>
                                 </div>
                                 <div class="flex justify-between text-sm">
                                     <span class="text-gray-500">This week</span>
                                     <span class="font-medium">2h 14min</span>
                                 </div>
                             </div>
                         </div>
                     </PhoneMockup>
                </div>
                <div class="w-full md:w-1/2 relative z-10">
                    <p class="text-xs uppercase tracking-widest text-gray-400 mb-2">Bank your discipline</p>
                    <h3 class="text-4xl md:text-5xl font-serif mb-6">Save earned time<br>for later</h3>
                    <p class="text-gray-400 leading-relaxed">
                        Discipline today becomes freedom tomorrow. Bank up to 1 hour of earned screen time and use it when you need it most.
                    </p>
                </div>
            </div>

             <!-- Card 3 -->
            <div class="bg-[#1C1C1C] rounded-[2rem] p-12 md:p-20 text-white relative overflow-hidden flex flex-col md:flex-row items-center gap-12">
                <div class="relative z-10 w-full md:w-1/2 flex justify-center">
                     <PhoneMockup>
                         <div class="p-6 flex flex-col h-full bg-white text-black justify-center">
                             <div class="bg-gray-50 rounded-xl p-6 mb-6 text-center">
                                 <div class="text-5xl mb-4">🔑</div>
                                 <h4 class="text-xl font-serif mb-2">Emergency Key</h4>
                                 <p class="text-sm text-gray-500">1 hour instant access</p>
                             </div>
                             <div class="text-center text-sm text-gray-500">
                                 2 keys remaining this week
                             </div>
                             <button class="bg-black text-white px-6 py-3 rounded-full w-full font-medium mt-6">
                                 Use Emergency Key
                             </button>
                         </div>
                     </PhoneMockup>
                </div>
                <div class="w-full md:w-1/2 relative z-10">
                    <p class="text-xs uppercase tracking-widest text-gray-400 mb-2">Life happens</p>
                    <h3 class="text-4xl md:text-5xl font-serif mb-6">Emergency keys<br>for urgent needs</h3>
                    <p class="text-gray-400 leading-relaxed">
                        Get 2 emergency unlocks per week. Each gives you 1 hour of app access. No exercise required, no judgment. Just flexibility for real life.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="py-24 bg-[#FCFAF7]">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl font-serif mb-12">How It Works</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Step 1 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-gray-100 rounded-full flex items-center justify-center text-xs">01</div>
                    <h3 class="text-2xl font-serif">Choose your distracting apps</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Instagram, TikTok, Twitter...</div>
                </div>
                 <!-- Step 2 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-gray-100 rounded-full flex items-center justify-center text-xs">02</div>
                    <h3 class="text-2xl font-serif">Set exercise requirements</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Pushups, squats, or planks</div>
                </div>
                 <!-- Step 3 -->
                <div class="bg-white p-8 rounded-xl aspect-[4/5] flex flex-col justify-between shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-8 h-8 bg-gray-100 rounded-full flex items-center justify-center text-xs">03</div>
                    <h3 class="text-2xl font-serif">Earn your screen time</h3>
                    <div class="text-xs text-gray-400 uppercase tracking-widest">Move to unlock</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonial -->
    <section class="bg-[#1C1C1C] text-white py-32">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-2 gap-16">
            <div>
                <h2 class="text-2xl font-serif mb-12">See what people are saying about Sixteen</h2>
                <h3 class="text-5xl md:text-7xl font-serif leading-tight">Broke my<br>late-night<br>scrolling.</h3>
            </div>
            <div class="flex flex-col justify-end">
                <p class="text-gray-400 text-lg leading-relaxed mb-8">
                    "I used to scroll TikTok until 2AM every night. Now I'm asleep before midnight. Sixteen doesn't just block apps—it rewires your daily routine. I've reclaimed hours I didn't realize I was losing."
                </p>
                <div>
                    <p class="font-bold">Knowledge Worker</p>
                    <p class="text-sm text-gray-500">App Store Review · 4.9 ⭐</p>
                </div>
                <div class="mt-12 flex justify-end">
                    <button class="text-white hover:opacity-70 transition-opacity">
                        <svg width="48" height="24" viewBox="0 0 50 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M0 12H48M48 12L38 2M48 12L38 22" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Share Section -->
    <section class="py-32 bg-[#FCFAF7] relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div class="relative z-10">
                <p class="text-3xl font-serif leading-relaxed mb-8 max-w-md">
                    Join remote knowledge workers who need deep focus but struggle with compulsive phone checking.
                </p>
                <AppButtons />
            </div>
            <div class="flex justify-center relative z-10">
                 <PhoneMockup>
                     <div class="flex items-center justify-center h-full bg-white">
                         <h1 class="text-4xl font-serif">Sixteen.</h1>
                     </div>
                 </PhoneMockup>
            </div>
        </div>
        <!-- Divider Line -->
        <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -z-0"></div>
    </section>

    <!-- Footer -->
    <footer class="pt-24 pb-12 px-6">
        <div class="max-w-7xl mx-auto flex flex-col items-center text-center">
            <div class="mb-16">
                <!-- Big Logo -->
                 <div class="relative inline-block">
                    <span class="text-[120px] md:text-[180px] font-serif leading-none">Sixteen</span>
                    <span class="text-[120px] md:text-[180px] font-serif leading-none text-black">.</span>
                 </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mb-16 text-sm text-gray-600">
                <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Product</span>
                    <a href="#">How It Works</a>
                    <a href="#">Features</a>
                </div>
                <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Resources</span>
                    <a href="#">Press Kit</a>
                    <a href="#">FAQ</a>
                </div>
                 <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Company</span>
                    <a href="mailto:keshav@sixteen.life">Contact</a>
                    <a href="#">About</a>
                </div>
                 <div class="flex flex-col gap-3 text-left md:text-center">
                    <span class="font-bold text-gray-900 uppercase tracking-widest text-xs mb-2">Legal</span>
                    <a href="#">Terms</a>
                    <a href="#">Privacy</a>
                </div>
            </div>

            <div class="flex flex-col md:flex-row items-center justify-between w-full border-t border-gray-200 pt-12 gap-8">
                <div class="text-xs text-gray-400">
                    © 2024 Tropolin Labs Private Limited
                </div>
                <div class="flex gap-6">
                    <!-- Social Icons -->
                    <a href="https://instagram.com/sixteen_app" class="text-gray-400 hover:text-gray-900 transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                    </a>
                    <a href="https://linkedin.com/company/sixteenapp" class="text-gray-400 hover:text-gray-900 transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    </a>
                    <a href="https://x.com/sixteenapp" class="text-gray-400 hover:text-gray-900 transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
                    </a>
                </div>
                <div>
                     <AppButtons />
                </div>
            </div>
        </div>
    </footer>
</div>

<style>
    /* Custom stroke text utility */
    .stroke-text {
        -webkit-text-stroke: 1px rgba(255, 255, 255, 0.5);
        color: transparent;
    }
</style>

