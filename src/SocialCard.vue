<script setup>
  defineProps({
    url: String,
    text: String,
    subtext: String
  })
</script>

<template>
  <div>
    <a
        :href="url"
        target="_blank"
        rel="noopener noreferrer"
        class="group mx-auto mt-4 grid h-20 w-full max-w-[750px] grid-cols-[48px_1fr_50px] items-center gap-4 rounded-xs bg-strong/10 px-6 text-strong transition-all duration-300 hover:bg-accent"
    >
      <!-- Logo -->
      <div class="flex items-center justify-center">
        <slot name="icon" />
      </div>

      <!-- Centered text -->
      <div class="flex flex-col items-center text-center">
        <span class="text-base font-bold uppercase tracking-[0.15em]">
          {{ text }}
        </span>

        <span class="mt-1 text-[10px] font-medium font-mono uppercase tracking-[0.15em] opacity-60">
          {{ subtext }}
        </span>
      </div>

      <!-- Arrow -->
      <span class="text-xl transition-transform duration-300 group-hover:translate-x-2">
        →
      </span>
    </a>
  </div>
</template>