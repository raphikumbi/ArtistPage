<script setup>
import { onMounted, ref, computed, nextTick, onUnmounted } from 'vue'
import { gsap } from 'gsap'
import { ScrollTrigger } from 'gsap/ScrollTrigger'
import { ScrollSmoother } from 'gsap/ScrollSmoother'
import UpcomingRelese from "./UpcomingRelese.vue";
import Header from "./Header.vue";
import Socials from "./Socials.vue";
import Releases from "./Releases.vue";
import SectionTitle from "./components/SectionTitle.vue";

gsap.registerPlugin(ScrollTrigger, ScrollSmoother)

let smoother

onMounted(() => {
  smoother = ScrollSmoother.create({
    wrapper: '#smooth-wrapper',
    content: '#smooth-content',
    smooth: 0.7,
    effects: true,
    smoothTouch: 0.5
  })

  ScrollTrigger.refresh()
})

onUnmounted(() => {
  smoother?.kill()
})
</script>

<template>
  <div id="smooth-wrapper" class="bg-white">
    <div id="smooth-content">

      <Header />

      <div class="relative mx-auto max-w-7xl p-5">

        <SectionTitle title="Find My Music" class="pt-10" />
        <Socials />

        <!-- <UpcomingRelese /> -->


        <SectionTitle title="Releases" class="pt-10" />
        <Releases />

      </div>
    </div>
  </div>
</template>
