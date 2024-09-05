<template>
  <div>
    <HomeCarousel />
    <HomeAboutUs />
    <!-- <HomeMaps /> -->
  </div>
</template>

<script setup>
definePageMeta({
  layout: "default",
  head: {
    title: "Home - Minis.Inc",
  },
});
onMounted(() => {
  document.title = "Home - Minis.Inc";
});
</script>