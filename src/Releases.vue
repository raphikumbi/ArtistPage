<script setup>
import ReleasedPeriode from "./components/ReleasedPeriode.vue";
import ReleasedSong from "./components/ReleasedSong.vue";
</script>
<template>
  <section id="releases" class="relative text-strong">

    <div class="">

      <!-- Section heading -->
      <ReleasedPeriode year="2026" />

      <ReleasedSong
          image="/images/release-hero.png"
          name="Hero"
          artists="Rapha Kumba · Axiom Label Group"
          date="15.05.2026"
      />

      <ReleasedPeriode year="2025" />

      <ReleasedSong
          image="/images/release-amen.png"
          name="Amen"
          artists="Rapha Kumba · Debby T.R · God's Nation"
          date="10.10.2025"
      />

      <ReleasedSong
          image="/images/release-allthislove.png"
          name="All This Love"
          artists="Rapha Kumba · Debby T.R"
          date="31.05.2025"
      />

      <ReleasedPeriode year="2024" />

      <ReleasedSong
          image="/images/release-runninghome.png"
          name="Running Home"
          artists="Rapha Kumba · Cloé"
          date="25.12.2024"
      />

      <ReleasedSong
          image="/images/release-storyoflove.png"
          name="Story Of Love"
          artists="Rapha Kumba · Cloé · God's Nation"
          date="04.10.2024"
      />

      <ReleasedSong
          image="/images/release-prochedetoi.png"
          name="Proche De Toi"
          artists="Rapha Kumba · Cloé"
          date="14.02.2024"
      />

      <ReleasedPeriode year="2022" />

      <ReleasedSong
          image="/images/release-beautifulscars.png"
          name="Beautiful Scars"
          artists="Rapha Kumba · Ever Worship · Serena"
          date="19.04.2022"
      />

    </div>
  </section>
</template>
