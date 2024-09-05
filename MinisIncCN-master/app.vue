<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup>
import { provideUseId } from '@headlessui/vue'
// Use SSR-safe IDs for Headless UI
provideHeadlessUseId(() => useId())

</script>
