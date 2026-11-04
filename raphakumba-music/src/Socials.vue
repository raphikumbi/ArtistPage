<script setup>
import SocialCard from "./SocialCard.vue";
</script>
<template>
  <section id="socials" class="relative overflow-hidden  pb-15">

      <!-- Introduction -->
      <p class="mb-16 text-sm leading-7 text-medium md:text-base">
        Discover my music and listen to my latest releases. Find me on your favourite streaming platform.
      </p>

      <!-- Social platforms -->
      <div class="items-center">

        <SocialCard
            url="https://open.spotify.com/intl-de/artist/4x20EEDdzmy1IRHx4ieikE"
            text="Spotify"
            subtext="Follow me on Spotify"
        >
          <template #icon>
            <svg
                viewBox="0 0 24 24"
                class="h-9 w-9 fill-current"
                aria-hidden="true"
            >
              <path d="M12 0C5.372 0 0 5.372 0 12s5.372 12 12 12 12-5.372 12-12S18.628 0 12 0zm5.498 17.303a.75.75 0 0 1-1.032.25c-2.827-1.728-6.386-2.12-10.58-1.16a.75.75 0 0 1-.336-1.462c4.59-1.052 8.525-.598 11.698 1.34a.75.75 0 0 1 .25 1.032zm1.47-3.27a.94.94 0 0 1-1.292.31c-3.236-1.99-8.17-2.565-11.997-1.402a.94.94 0 1 1-.547-1.8c4.373-1.327 9.806-.685 13.526 1.601a.94.94 0 0 1 .31 1.291zm.126-3.405C15.21 8.27 8.78 8.058 5.06 9.188a1.125 1.125 0 1 1-.653-2.153c4.27-1.296 11.37-1.045 15.85 1.613a1.125 1.125 0 0 1-1.163 1.98z"/>
            </svg>
          </template>
        </SocialCard>

        <SocialCard
            url="https://music.apple.com/us/artist/rapha-kumba/1736984471"
            text="Apple Music"
            subtext="Follow me on Apple Music"
        >
          <template #icon>
            <svg
                viewBox="0 0 24 24"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
                class="h-8 w-8 "
            >
              <path d="M21.5 2.5a1 1 0 0 0-1.2-1L8.8 3.8A1 1 0 0 0 8 4.8v12.1a3.5 3.5 0 1 0 2 3.1V8.2l9.5-2.1v8.8a3.5 3.5 0 1 0 2 3.1V2.5Z"/>
            </svg>
          </template>
        </SocialCard>

        <SocialCard
            url="https://www.youtube.com/@raphakumba"
            text="Youtube"
            subtext="Follow me on Youtube"
        >
          <template #icon>
            <svg viewBox="0 0 24 24"
                 fill="currentColor"
                 class="h-9 w-9 text-strong">
              <path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.5 12 3.5 12 3.5s-7.505 0-9.376.55A3.016 3.016 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136C4.495 20.5 12 20.5 12 20.5s7.505 0 9.376-.55a3.016 3.016 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.6 15.5v-7l6.3 3.5-6.3 3.5z"/>
            </svg>
          </template>
        </SocialCard>

        <SocialCard
            url="https://www.instagram.com/rapha.kumba"
            text="Instagram"
            subtext="Follow me on Instagram"
        >
          <template #icon>
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"
                 stroke-width="1.7"
                 class="h-9 w-9 text-strong">
              <rect x="2" y="2" width="20" height="20" rx="5"/>
              <circle cx="12" cy="12" r="4.5"/>
              <circle cx="18" cy="6" r="1" fill="currentColor" stroke="none"/>
            </svg>
          </template>
        </SocialCard>

      </div>

  </section>
</template>
