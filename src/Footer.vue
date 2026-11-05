<template>
  <footer class="relative overflow-hidden bg-strong text-strong">

    <!-- Background image -->
    <div
        class="absolute inset-0 bg-cover bg-center bg-no-repeat"
        style="background-image: url('/images/Hero.png')"
    ></div>

    <!-- Dark overlay -->
    <div class="absolute inset-0 bg-linear-to-b from-black/10 via-black/45 to-black"></div>

    <!-- Footer content -->
    <div class="relative mx-auto flex max-w-7xl flex-col items-center px-6 pt-20 pb-8 text-center">

      <!-- Artist name -->
      <h2 class="text-3xl font-black tracking-[0.2em]">
        RAPHA KUMBA
      </h2>

      <!-- Copyright -->
      <p class="mt-8 border-t border-white/10 pt-6 text-xs text-white/40">
        © {{ new Date().getFullYear() }} Rapha Kumba. All rights reserved.
      </p>

    </div>
  </footer>
</template>