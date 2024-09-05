<template>
  <div class="grid grid-rows-2 gap-4">
    <div
      class="border-2 relative w-24 aspect-square rounded-full border-dark-blue mx-auto grid bg-light-blue"
    >
      <p class="text-center font-bold text-2xl md:text-3xl place-self-center">
        {{ number }}
      </p>
    </div>
    <p class="text-center text-lg px-8 md:px-0">
      {{ content }}
    </p>
  </div>
</template>

<script setup>
defineProps({
  number: {
    type: String,
    required: true,
  },
  content: {
    type: String,
    required: true,
  },
});
</script>
