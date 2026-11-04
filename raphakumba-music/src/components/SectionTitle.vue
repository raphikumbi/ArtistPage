<script setup>
defineProps({
  title: String
})
</script>

<template>
  <h2 class="font-display text-7xl uppercase tracking-wide md:text-8xl pt-2 pb-2 text-strong">
    {{ title }}<span class="text-accent">.</span>
  </h2>
</template>