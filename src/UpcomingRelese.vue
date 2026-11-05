
<template>
  <section class="relative overflow-hidden  px-6 pt-15 pb-15 text-white">

    <div class="relative mx-auto max-w-7xl">

      <div class="grid items-center gap-14 md:grid-cols-2 md:gap-20">

        <!-- Album artwork -->
        <div class="relative mx-auto w-full max-w-130">

          <div class="relative aspect-square overflow-hidden shadow-2xl shadow-black/60">
            <img
                src="/images/release-whenallgoesdim.png"
                alt="When All Goes Dim artwork"
                class="h-full w-full object-cover transition-transform duration-1000 hover:scale-105"
            />
          </div>

        </div>

        <!-- Release information -->
        <div class="flex flex-col items-start">

          <div class="flex items-center gap-3">
            <span class="relative flex h-2.5 w-2.5">
              <span class="absolute inline-flex h-full w-full animate-ping rounded-full bg-accent opacity-50"></span>
              <span class="relative inline-flex h-2.5 w-2.5 rounded-full bg-accent"></span>
            </span>

            <span class="text-xs font-semibold uppercase tracking-[0.25em] text-accent">
              Upcoming Single
            </span>
          </div>

          <h2 class="mt-8 max-w-xl font-display text-5xl uppercase leading-[0.95] tracking-tight sm:text-6xl lg:text-7xl text-strong">
            When All
            <span class="block">Goes Dim</span>
          </h2>
<!--
          <p class="mt-7 text-sm tracking-wide text-zinc-400">
            In collaboration with God's Nation
          </p>
-->
          <!-- Release date -->
          <div class="mt-12 border-l-2 border-accent pl-6">
            <p class="text-xs uppercase tracking-[0.3em] text-zinc-500">
              Out everywhere
            </p>
            <p class="mt-2 text-4xl font-semibold tracking-wide sm:text-5xl text-strong">
              11.12.2026
            </p>
          </div>

          <!-- Pre-save -->
<!--
          <a
              href="#"
              target="_blank"
              rel="noopener noreferrer"
              class="group mt-12 inline-flex items-center gap-5 bg-[#1DB954] px-8 py-5 text-black transition-all duration-300 hover:bg-white"
          >
            <svg
                viewBox="0 0 24 24"
                class="h-6 w-6 fill-current"
                aria-hidden="true"
            >
              <path d="M12 0C5.372 0 0 5.372 0 12s5.372 12 12 12 12-5.372 12-12S18.628 0 12 0zm5.498 17.303a.75.75 0 0 1-1.032.25c-2.827-1.728-6.386-2.12-10.58-1.16a.75.75 0 0 1-.336-1.462c4.59-1.052 8.525-.598 11.698 1.34a.75.75 0 0 1 .25 1.032zm1.47-3.27a.94.94 0 0 1-1.292.31c-3.236-1.99-8.17-2.565-11.997-1.402a.94.94 0 1 1-.547-1.8c4.373-1.327 9.806-.685 13.526 1.601a.94.94 0 0 1 .31 1.291zm.126-3.405C15.21 8.27 8.78 8.058 5.06 9.188a1.125 1.125 0 1 1-.653-2.153c4.27-1.296 11.37-1.045 15.85 1.613a1.125 1.125 0 0 1-1.163 1.98z"/>
            </svg>

            <span class="text-xs font-bold uppercase tracking-[0.2em]">
              Pre-save on Spotify
            </span>

            <span class="transition-transform duration-300 group-hover:translate-x-2">
              →
            </span>
          </a>
          -->
        </div>
      </div>
    </div>
  </section>
</template>
