<template>
  <div class="bg-light-blue pb-16">
    <div class="container mx-auto">
      <h1 class="text-center text-5xl font-bold mb-20">主要特点</h1>
      <div class="flex flex-col items-center justify-center gap-8">
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
          <ProductsFeaturesCard
            number="1"
            content="支持数字和模拟控制通道，实现伺服电机、阀门和其他执行器的精确管理。"
          />
          <ProductsFeaturesCard
            number="2"
            content="包括数字和模拟测量通道，用于精确的传感器数据收集和处理。"
          />
          <ProductsFeaturesCard
            number="3"
            content="通过支持复杂的测量和控制任务，确保稳定的性能。"
          />
          <ProductsFeaturesCard
            number="4"
            content="带有MgcTest软件，可实现无缝集成和易于操作，以及用于后端执行的MgcDll。"
          />
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <ProductsFeaturesCard
            number="5"
            content="可在计算机模式、网络模式或独立模式下运行，为各种使用场景提供灵活性。"
          />
          <ProductsFeaturesCard
            number="6"
            content="设计用于各种传感器和执行器，包括数字和模拟。"
          />
          <ProductsFeaturesCard
            number="7"
            content="将高性能与具有竞争力的价格相结合，使其成为升级工业自动化系统的绝佳选择。"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
