<template>
  <header class="absolute top-0 z-50 grid h-auto sm:h-18 w-full select-none items-center md:bg-black/0 md:backdrop-blur-none bg-black/20 backdrop-blur-sm">
    <div class="container px-3 sm:px-6 mx-auto grid grid-cols-1 items-center gap-4 sm:gap-6 py-3 sm:py-0">
      <!-- МОБИЛЬНОЕ МЕНЮ (видно только на мобилах) -->
      <div class="flex sm:hidden justify-between items-center">
        <button 
          @click="isMenuOpen = !isMenuOpen"
          class="p-2 rounded-lg hover:bg-white/10 transition"
          aria-label="Меню">
          <i :class="isMenuOpen ? 'fas fa-times' : 'fas fa-bars'" class="text-xl text-white"></i>
        </button>
      </div>

      <!-- НАВИГАЦИЯ -->
      <nav :class="['flex', 'flex-col', 'sm:flex-row', 'sm:justify-center', 'gap-5', 'sm:gap-2', {'hidden sm:flex': !isMenuOpen, 'flex': isMenuOpen}]">
        <a class="flex rounded-full  transition hover:bg-teal-100 dark:hover:bg-teal-300/10 -my-2 px-2.5 sm:px-4 py-2 text-xs sm:text-sm font-medium text-teal-500 dark:text-teal-400"
          href="/"
          @click="isMenuOpen = false">Главная
        </a>

        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-2.5 sm:px-4 py-2 text-xs sm:text-sm font-medium text-zinc-700 dark:text-zinc-100 hover:text-black dark:hover:text-white"
          href=""
          @click="isMenuOpen = false">Проекты</a>

        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-2.5 sm:px-4 py-2 text-xs sm:text-sm font-medium text-zinc-700 dark:text-zinc-100 hover:text-black dark:hover:text-white"
          href=""
          @click="isMenuOpen = false">Персонаж</a>

        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-2.5 sm:px-4 py-2 text-xs sm:text-sm font-medium text-zinc-700 dark:text-zinc-100 hover:text-black dark:hover:text-white"
          href=""
          @click="isMenuOpen = false">Арты</a>
      </nav>
    </div>
  </header>
</template>

<script>
export default { 
  name: "TheHeader",
  data() {
    return {
      isMenuOpen: false
    }
  }
};
</script>

<style></style>
