<script setup>
defineProps({
  image: String,
  name: String,
  artists: String,
  date: String
})
</script>

<template>
  <div class="h-22.5 p-2 grid grid-cols-[90px_1fr] gap-4 mb-8">
    <img
        :src="image"
        alt="Release artwork"
        class="h-full w-full object-cover"
    />

    <div>
      <p class="mb-2 text-xs uppercase tracking-[0.2em] text-strong/80">
        {{ date }}
      </p>

      <h4 class="mb-1 font-display text-3xl uppercase tracking-wider text-strong">
        {{ name }}
      </h4>

      <p class="text-sm text-strong/80">
        {{ artists }}
      </p>
    </div>

  </div>
</template>