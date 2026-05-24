---
layout: home
title: "My Projects"
permalink: /projects/
---
<div class="min-h-screen bg-gray-50 text-gray-900 overflow-hidden relative pt-24 pb-16 px-4">
    
    <!-- Background glowing orbs -->
    <div class="absolute top-0 left-1/4 w-96 h-96 bg-blue-600/20 rounded-full blur-[100px] pointer-events-none"></div>
    <div class="absolute bottom-0 right-1/4 w-96 h-96 bg-teal-500/20 rounded-full blur-[100px] pointer-events-none"></div>

    <section class="relative z-10 max-w-6xl pt-36 mx-auto" x-data="{ show: false }" x-init="setTimeout(() => show = true, 500)">
        <div class="text-center mb-16" x-show="show" x-transition.opacity.duration.1000ms.translate.y.20px>
            <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight text-gray-900 mb-4">My Projects</h1>
            <p class="text-lg md:text-xl text-gray-500 max-w-2xl mx-auto font-light">A collection of systems and applications I've built, ranging from management platforms to utility tools.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8" x-show="show" x-transition.opacity.duration.1000ms.delay.300ms.translate.y.20px>
            
            <!-- LabRMS -->
            <a href="#" class="group block bg-white/80 backdrop-blur-sm border border-gray-200/80 rounded-3xl p-8 hover:-translate-y-2 hover:shadow-xl hover:shadow-blue-500/10 hover:border-blue-400/50 transition-all duration-300">
                <div class="w-14 h-14 rounded-2xl bg-blue-50 text-blue-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path></svg>
                </div>
                <h3 class="text-2xl font-bold text-gray-900 mb-3">LabRMS</h3>
                <p class="text-gray-500 leading-relaxed">A comprehensive platform for managing laboratory operations and inventory.</p>
            </a>

            <!-- ScheduleIt -->
            <a href="/scheduleit" class="group block bg-white/80 backdrop-blur-sm border border-gray-200/80 rounded-3xl p-8 hover:-translate-y-2 hover:shadow-xl hover:shadow-blue-500/10 hover:border-blue-400/50 transition-all duration-300">
                <div class="w-14 h-14 rounded-2xl bg-teal-50 text-teal-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                </div>
                <h3 class="text-2xl font-bold text-gray-900 mb-3">ScheduleIt</h3>
                <p class="text-gray-500 leading-relaxed">An intuitive financial tool designed to track expenses, manage budgets, and provide insightful analytics.</p>
            </a>

            <!-- HRMS -->
            <a href="#" class="group block bg-white/80 backdrop-blur-sm border border-gray-200/80 rounded-3xl p-8 hover:-translate-y-2 hover:shadow-xl hover:shadow-blue-500/10 hover:border-blue-400/50 transition-all duration-300">
                <div class="w-14 h-14 rounded-2xl bg-indigo-50 text-indigo-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                </div>
                <h3 class="text-2xl font-bold text-gray-900 mb-3">HRMS</h3>
                <p class="text-gray-500 leading-relaxed">A robust HR solution for managing employee data, attendance and payroll.</p>
            </a>

            <!-- Nyxbin -->
            <a href="#" class="group block bg-white/80 backdrop-blur-sm border border-gray-200/80 rounded-3xl p-8 hover:-translate-y-2 hover:shadow-xl hover:shadow-blue-500/10 hover:border-blue-400/50 transition-all duration-300">
                <div class="w-14 h-14 rounded-2xl bg-purple-50 text-purple-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path></svg>
                </div>
                <h3 class="text-2xl font-bold text-gray-900 mb-3">Nyxbin</h3>
                <p class="text-gray-500 leading-relaxed">A fast, secure pastebin service for sharing code snippets and text notes with built-in syntax highlighting.</p>
            </a>

            <!-- CMS -->
            <a href="#" class="group block bg-white/80 backdrop-blur-sm border border-gray-200/80 rounded-3xl p-8 hover:-translate-y-2 hover:shadow-xl hover:shadow-blue-500/10 hover:border-blue-400/50 transition-all duration-300">
                <div class="w-14 h-14 rounded-2xl bg-rose-50 text-rose-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9.5a2.5 2.5 0 00-2.5-2.5H15M9 11l3 3m0 0l3-3m-3 3V8"></path></svg>
                </div>
                <h3 class="text-2xl font-bold text-gray-900 mb-3">Latem III</h3>
                <p class="text-gray-500 leading-relaxed">A flexible and scalable content management system built for rapid content creation and seamless publishing.</p>
            </a>

        </div>
    </section>
</div>
