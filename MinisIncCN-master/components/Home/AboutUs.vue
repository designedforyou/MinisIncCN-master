<template>
  <div class="container mx-auto">
    <h1 class="text-5xl md:text-7xl font-bold text-center">关于我们</h1>
    <div class="grid grid-cols-1 lg:grid-cols-2 mt-8 gap-8">
      <img class="w-full" src="/Home/About Us.png" alt="" />
      <div class="flex flex-col">
        <p class="text-center px-8 lg:px-0 lg:text-justify">
          我们是一家专业的公司，专注于产品，应用和服务的控制和测试技术解决方案公司。
          经过多年的研究，新的控制器MGC-1624已成功推出。
          该产品代表了一个革命性的突破，有望推动行业向前发展。
          公司将紧跟市场需求，坚持不断的技术创新，开发更多更好的新产品。
        </p>
        <div
          class="flex items-center justify-center lg:justify-start lg:items-start lg:pt-4 py-8 lg:py-0"
        >
          <NuxtLink
            to="/about"
            class="bg-black text-white py-3 px-6 italic rounded-lg w-fit"
          >
            了解更多
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
