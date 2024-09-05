<template>
  <div>
    <h1
      class="container mx-auto text-center text-6xl md:text-7xl font-bold pb-4 md:pb-8"
    >
      MGC-1624
    </h1>
  </div>
  <div class="flex justify-center">
    <div class="w-3/4 md:w-1/2">
      <Banner bannerImage="Products/1_Front.png" />
    </div>
  </div>
  <Slogan
    title="摘要"
    content="MGC-1624控制器是经过多年的研究和创新而开发的最先进的控制系统。 它通过16个闭环控制通道和24个测量通道提供卓越的性能，使其处于行业前沿。 这款多功能控制器非常适合各种应用，包括自动化设备、试验机和其他工业设备。"
  />
  <div class="relative flex justify-center lg:mt-8">
    <div class="relative z-10 w-3/4 md:w-1/2">
      <Banner bannerImage="Products/2_Left_Behind.png" />
    </div>
    <div class="absolute z-0 bottom-0 left-0 w-full h-1/2 bg-light-blue"></div>
  </div>
  <ProductsFeatures />
  <ProductsApplications />
  <ProductsSpecifications />
  <p
    class="container mx-auto py-8 text-center text-dark-blue text-3xl font-bold w-2/3"
  >
    MGC-1624是一款通用控制器,适用于各种控制和测量应用场景;
    也可以根据用户需求通过二次开发实现专用。
  </p>
  <ProductsBullets />
  <ProductsSoftware />
  <ProductsBuy />
</template>

<script setup>
definePageMeta({
  layout: "default",
  head: {
    title: "Our Products - Minis.Inc",
  },
});
onMounted(() => {
  document.title = "Our Products - Minis.Inc";
});
</script>