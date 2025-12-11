<template>
  <!-- <header
    class="absolute top-0 left-0 w-full z-50 grid h-18 w-full select-none items-center border-b transition border-transparent"> -->
  <header class="sticky top-0 z-50 grid h-18 w-full select-none items-center border-b transition border-transparent">
    <div class="container px-6 mx-auto grid grid-cols-1 items-center gap-6">
      <!-- ТЕКСТОВОЕ МЕНЮ (оставлено как в оригинале) -->
      <nav class="flex justify-center gap-2">
        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-4 py-2 text-sm font-medium text-teal-500 dark:text-teal-400"
          href="/">Главная</a>

        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-4 py-2 text-sm font-medium text-zinc-700 dark:text-zinc-100 hover:text-black dark:hover:text-white"
          href="/about">Мои проекты</a>

        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-4 py-2 text-sm font-medium text-zinc-700 dark:text-zinc-100 hover:text-black dark:hover:text-white"
          href="/rules">Персонаж</a>

        <a class="flex rounded-full transition hover:bg-zinc-100 dark:hover:bg-white/10 -my-2 px-4 py-2 text-sm font-medium text-zinc-700 dark:text-zinc-100 hover:text-black dark:hover:text-white"
          href="/wiki">Арты</a>
      </nav>
    </div>
  </header>
</template>

<script>
export default { name: "TheHeader" };
</script>

<style></style>
