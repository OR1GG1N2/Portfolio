<template>
    <section class="min-h-screen flex items-center justify-center px-4 bg">
        <div
            class="relative max-w-3xl w-full rounded-2xl hover:bg-white/15 transition easy-in-out bg-white/5 backdrop-blur-xl border border-white/10 shadow-xl p-6 md:p-10 ">
            <div class="flex flex-col md:flex-row items-center gap-6">
                <!-- Avatar -->
                <div class="shrink-0">
                    <img src="/src/assets/photo_2025-12-10_16-12-07.jpg" alt="Avatar"
                        class="w-32 h-32 md:w-40 md:h-40 rounded-full object-cover border border-white/20 shadow-[0_0_30px_rgba(120,240,200,0.6)]" />
                </div>


                <!-- Content -->
                <div class="text-center md:text-left">
                    <h1 class="text-2xl text-white unbound--bold md:text-3xl font-semibold tracking-tight">
                        Максим
                    </h1>


                    <p class="mt-2 text-zinc-400 max-w-xl unbound--light">
                        Frontend разработчик и дизайнер. Vue / Next.js / Tailwind.
                        Стример, художник и просто хороший человек/кот.
                    </p>


                    <!-- Buttons -->
                    <div class="mt-5 flex flex-wrap justify-center md:justify-start gap-3 unbound--regular">
                        <a href="#projects"
                            class="px-4 py-2 rounded-xl bg-white text-black text-sm font-medium hover:opacity-90 transition">
                            Проекты
                        </a>


                        <a href="#contact"
                            class="px-4 py-2 rounded-xl border border-white/20 text-white text-sm hover:bg-white/5 transition">
                            Контакты
                        </a>


                        <a href="https://github.com/" target="_blank"
                            class="px-4 py-2 rounded-xl border border-white/10 text-zinc-400 text-sm hover:text-white hover:border-white/30 transition">
                            GitHub
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>














<style></style>

<script>
export default {

}
</script>