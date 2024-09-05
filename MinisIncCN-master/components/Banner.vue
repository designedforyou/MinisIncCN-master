<template>
  <div class="lg:container lg:mx-auto pb-4 md:pb-16 flex items-center justify-center">
    <img class="md:w-full" :src="bannerImage" alt="Banner" />
  </div>
</template>

<script setup>
defineProps({
  bannerImage: {
    type: String,
    required: true,
  },
});
</script>