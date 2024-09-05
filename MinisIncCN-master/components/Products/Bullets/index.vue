<template>
  <div class="container mx-auto py-16">
    <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 place-items-center">
      <ProductsBulletsCard
        img="Products/One_For_One.png"
        title="一拖一"
        content="一个控制器控制一台设备,例如试验机、三
轴测量机、数控机床、工业机器人等等。"
      />
      <ProductsBulletsCard
        img="Products/More_Than_One_Place.png"
        title="一地多"
        content="一个控制器控制多台设备,例如控制多台播。
变试验机/松地试验机,或一个控制器控制
一个小型实验室的所有设备等等。"
      />
      <ProductsBulletsCard
        img="Products/One_More_Place.png"
        title="多地一"
        content="通过多控制器互连、或通过网络系统(例如
同域网),实现多台控制器控制一个设备
群,例如自动化生产线、飞机顾振测试系统
等。"
      />
    </div>
  </div>
</template>

<script setup>
</script>
