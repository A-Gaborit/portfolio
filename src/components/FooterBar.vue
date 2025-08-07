<template>
  <footer class="w-full text-end text-sm text-primary-500">
    <div
      class="absolute left-2 md:left-5 right-0 translate-y-[-50%] flex items-center text-white gap-1 md:gap-3 z-2 md:z-0 dark:text-black-soft"
    >
      <a href="https://github.com/A-Gaborit" target="_blank">
        <i class="fa-brands fa-github text-xl lg:text-3xl"></i>
      </a>
      <a href="https://www.linkedin.com/in/audrey-gaborit/" target="_blank">
        <i class="fa-brands fa-linkedin text-xl lg:text-3xl"></i>
      </a>
      <hr class="w-full border-white border-2 mx-10 dark:border-black-soft" />
    </div>
    <p class="pt-4">© {{ new Date().getFullYear() }} Audrey Gaborit</p>
  </footer>
</template>
