---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "My Portfolio"
---
<div class="min-h-screen bg-gray-50 text-gray-900 overflow-hidden relative">
    
    <!-- Background glowing orbs -->
    <div class="absolute top-0 left-1/4 w-96 h-96 bg-blue-600/20 rounded-full blur-[100px] pointer-events-none"></div>
    <div class="absolute bottom-0 right-1/4 w-96 h-96 bg-teal-500/20 rounded-full blur-[100px] pointer-events-none"></div>

    <!-- Hero / About Section -->
    <section id="about-section" class="relative z-10 pt-36 pb-16 px-4 max-w-5xl mx-auto flex flex-col items-center text-center" x-data="{ show: false }" x-init="setTimeout(() => show = true, 500)">
        <div x-show="show" x-transition.opacity.duration.1000ms.translate.y.20px>
            <a href="#" class="inline-block relative group">
                <div class="absolute -inset-1 bg-gradient-to-r from-blue-500 to-teal-400 rounded-full blur opacity-25 group-hover:opacity-75 transition duration-500"></div>
                <img class="relative w-40 h-40 object-cover rounded-full border-4 border-white shadow-xl" src="/images/vector-image.jpg" alt="Gabriel Jay" />
            </a>
            <h1 class="mt-8 text-5xl md:text-6xl font-extrabold tracking-tight">
                Hi! I’m <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-teal-300">Gabriel Jay</span>
            </h1>
            <p class="mt-4 text-xl md:text-2xl text-gray-500 font-light tracking-wide uppercase letter-spacing-2">Web Developer</p>
        </div>
    </section>

    <!-- Technologies Section -->
    <section id="technologies-used-section" class="relative z-10 py-16 px-4" x-data="{ show: false }" x-init="setTimeout(() => show = true, 800)">
        <div class="max-w-6xl mx-auto" x-show="show" x-transition.opacity.duration.1000ms.translate.y.20px>
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Technologies</h2>
                <p class="text-gray-500 max-w-2xl mx-auto">Listing some of the languages, tools, and frameworks I’ve used for development.</p>
            </div>
            
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-6">
                <!-- PHP -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-indigo-500/10 hover:border-indigo-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(79,70,229,0.6)]" src="/images/technologies/php-logo.png" alt="PHP" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-indigo-600 transition-colors duration-300">PHP</span>
                </div>
                <!-- Laravel -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-rose-500/10 hover:border-rose-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(225,29,72,0.6)]" src="/images/technologies/laravel-logo.png" alt="Laravel" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-rose-600 transition-colors duration-300">Laravel</span>
                </div>
                <!-- MySQL -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-cyan-500/10 hover:border-cyan-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(8,145,178,0.6)]" src="/images/technologies/mysql-logo.png" alt="MySQL" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-cyan-600 transition-colors duration-300">MySQL</span>
                </div>
                <!-- JavaScript -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-amber-500/10 hover:border-amber-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(245,158,11,0.6)]" src="/images/technologies/javascript-logo.png" alt="JavaScript" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-amber-500 transition-colors duration-300">JavaScript</span>
                </div>
                <!-- Sass -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-pink-500/10 hover:border-pink-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(236,72,153,0.6)]" src="/images/technologies/sass-logo.png" alt="Sass" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-pink-500 transition-colors duration-300">Sass</span>
                </div>
                <!-- Java -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-orange-500/10 hover:border-orange-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(234,88,12,0.6)]" src="/images/technologies/java-logo.png" alt="Java" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-orange-600 transition-colors duration-300">Java</span>
                </div>
                <!-- React Native -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-sky-500/10 hover:border-sky-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(14,165,233,0.6)]" src="/images/technologies/react-native-logo.jpg" alt="React Native" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-sky-500 transition-colors duration-300">React Native</span>
                </div>
                <!-- Node.js -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-emerald-500/10 hover:border-emerald-400/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(5,150,105,0.6)]" src="/images/technologies/nodejs-logo.png" alt="Node.js" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-emerald-600 transition-colors duration-300">Node.js</span>
                </div>
                <!-- GitHub -->
                <div class="group bg-white/60 backdrop-blur-sm border border-gray-200/80 rounded-2xl p-6 flex flex-col items-center justify-center hover:-translate-y-2 hover:shadow-xl hover:shadow-gray-800/10 hover:border-gray-800/50 transition-all duration-300 cursor-pointer">
                    <img class="w-20 h-20 object-contain opacity-80 group-hover:opacity-100 transition-all duration-300 group-hover:scale-110 filter group-hover:drop-shadow-[0_0_12px_rgba(17,24,39,0.6)]" src="/images/technologies/github-logo.png" alt="GitHub" />
                    <span class="mt-4 text-sm font-semibold text-gray-600 group-hover:text-gray-900 transition-colors duration-300">GitHub</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Quote Section -->
    <section id="simple-quote-section" class="relative z-10 py-24 px-4" x-data="{ show: false }" x-init="setTimeout(() => show = true, 1100)">
        <div class="max-w-4xl mx-auto" x-show="show" x-transition.opacity.duration.1000ms.translate.y.20px>
            <div class="bg-gradient-to-br from-white to-gray-50 border border-gray-200 rounded-[2rem] p-10 md:p-16 shadow-xl relative overflow-hidden">
                <!-- Quote Icon -->
                <div class="absolute top-8 left-8 text-blue-500/20 text-8xl font-serif">"</div>
                
                <blockquote class="relative z-10 text-center">
                    <p class="text-xl md:text-3xl text-gray-700 font-light italic leading-relaxed mb-8">
                        When you want something, all the universe conspires in helping you to achieve it.
                    </p>
                    <footer class="flex items-center justify-center space-x-4">
                        <div class="w-12 h-[1px] bg-blue-500"></div>
                        <cite class="text-blue-400 font-semibold tracking-wide uppercase text-sm">Paulo Coelho</cite>
                        <div class="w-12 h-[1px] bg-blue-500"></div>
                    </footer>
                </blockquote>
            </div>
        </div>
    </section>

</div>