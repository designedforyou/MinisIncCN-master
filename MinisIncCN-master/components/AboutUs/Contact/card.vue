<template>
  <a
    :href="href"
    target="_blank"
    class="w-64 h-64 p-8 shadow-lg bg-[#fafafa] shadow-black/20 rounded-2xl"
  >
    <div class="flex flex-col items-center justify-center relative">
      <img class="w-16 h-16 mb-4" :src="img" alt="ContactIcon" />
      <div class="absolute bottom-0">
        <p class="text-center text-lg font-bold">
          {{ content }}
        </p>
      </div>
    </div>
  </a>
</template>



<script setup>
defineProps({
  img: {
    type: String,
    required: true,
  },
  content: {
    type: String,
    required: true,
  },
  href: {
    type: String,
    required: true,
  },
});
</script>