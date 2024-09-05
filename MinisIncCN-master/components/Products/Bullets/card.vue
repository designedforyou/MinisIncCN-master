<template>
  <div class="flex flex-col items-center justify-start gap-4">
    <img class="w-1/3" :src="img" alt="" />
    <h2 class="text-xl font-bold text-center">
      {{ title }}
    </h2>
    <p class="text-center px-8 lg:px-0">
      {{ content }}
    </p>
  </div>
</template>

<script setup>
defineProps({
  img: String,
  title: String,
  content: String,
});
</script>
