<script setup>
</script>
<template>
  <section class="relative flex min-h-screen w-full items-center justify-center bg-black">
    <!-- Background image -->
    <div
        class="absolute inset-0 bg-cover bg-center bg-no-repeat"
        style="background-image: url('/images/Hero.png')"
    ></div>

    <!-- Dark overlay -->
    <div class="absolute inset-0 bg-black/35"></div>

    <!-- Content -->
    <div class="relative z-10 flex flex-col items-center text-center px-6">

      <h1
          class="font-display text-6xl sm:text-8xl md:text-9xl tracking-[0.08em] text-white uppercase"
      >
        Rapha Kumba
      </h1>

      <p
          class="mt-5 flex items-center gap-3 text-[12px] font-medium uppercase tracking-[0.35em] text-white/75"
      >
        <span>Music</span>
        <span class="h-1 w-1 rounded-full bg-white/70"></span>
        <span>Faith</span>
        <span class="h-1 w-1 rounded-full bg-white/70"></span>
        <span>Jesus</span>
      </p>

    </div>
  </section>
</template>