<script setup>
defineProps({
  year: String
})
</script>

<template>
  <div class="mb-8 mt-12 flex items-center gap-6">
    <h3 class="font-display text-4xl tracking-wide text-strong md:text-5xl">
      {{ year }}
    </h3>
    <div class="h-px flex-1 bg-strong/25"></div>
  </div>
</template>