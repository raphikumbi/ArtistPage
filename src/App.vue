<script setup>
import { onMounted, ref, computed, nextTick, onUnmounted } from 'vue'
import { gsap } from 'gsap'
import { ScrollTrigger } from 'gsap/ScrollTrigger'
import { ScrollSmoother } from 'gsap/ScrollSmoother'
import UpcomingRelese from "./UpcomingRelese.vue";
import Header from "./Header.vue";
import Footer from "./Footer.vue";
import Socials from "./Socials.vue";
import SectionTitle from "./components/SectionTitle.vue";
import Divider from "./Divider.vue";

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
  <div id="smooth-wrapper">
    <div id="smooth-content">

      <Header />

      <Divider />

      <div class="bg-[#17121A]">
        <div class="relative mx-auto max-w-7xl p-5">
          <SectionTitle title="Find My Music" class="pt-10" />
          <Socials />
        </div>
      </div>

      <Divider />

      <div class="bg-[#191516]">
        <div class="relative mx-auto max-w-7xl p-5">
          <SectionTitle title="Upcoming Release" class="pt-10" />
          <UpcomingRelese />
        </div>
      </div>

      <Divider />

      <Footer class="pt-10"/>

    </div>
  </div>
</template>
