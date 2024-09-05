<template>
  <div class="container mx-auto p-4 md:p-8 md:-mt-8 text-center">
    <h1 class="text-5xl font-bold mb-8">{{ title }}</h1>
    <div>
      <p class="text-center">
        {{ content }}
      </p>
    </div>
  </div>
</template>

<script setup>
defineProps({
  title: {
    type: String,
    required: true,
  },
  content: {
    type: String,
    required: true,
  },
});
</script>
