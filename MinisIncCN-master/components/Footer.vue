<template>
  <footer class="hidden md:block container mx-auto px-8">
    <div class="grid grid-cols-2 py-8">
      <div class="flex flex-col justify-between items-start gap-3">
        <img class="w-64" src="/Logo.png" alt="LOGO" />
        <p class="w-96">
          我们是一家专业的公司，专注于产品，应用和服务的控制和测试技术解决方案公司。
        </p>
      </div>
      <div class="flex flex-col justify-between items-end h-full">
        <NuxtLink to="/" :class="{ 'font-bold': $route.path === '/' }"
          >首页</NuxtLink
        >
        <NuxtLink
          to="/product"
          :class="{ 'font-bold': $route.path === '/product' }"
          >产品目录</NuxtLink
        >
        <NuxtLink to="/about" :class="{ 'font-bold': $route.path === '/about' }"
          >关于我们</NuxtLink
        >
        <NuxtLink
          to="https://www.wenjuan.com/s/UZBZJvlmuC/"
          target="_blank"
          >我要订购!</NuxtLink
        >
      </div>
    </div>

    <hr />

    <div class="flex items-center justify-between py-6">
      <div class="">
        <p>
          Copyright © 2024 minis-tech.com All Rights Reserved.
          上海明尼诗电子科技有限公司 版权所有
        </p>
      </div>
      <div class="flex items-center justify-between gap-8">
        <a href="tel:021-51593021">
          <img class="aspect-square w-6" src="/Icons/Icon1.png" alt="" />
        </a>
        <a :href="mailTo">
          <img
            class="aspect-square w-6"
            src="/Icons/Icon2.png"
            alt="Email Icon"
          />
        </a>
        <a href="https://j.map.baidu.com/31/A8q">
          <img
            class="aspect-square w-6"
            src="/Icons/Icon3.png"
            alt="Email Icon"
          />
        </a>
      </div>
    </div>
  </footer>
  <footer
    class="md:hidden container mx-auto px-8 flex flex-col justify-center items-center pt-8"
  >
    <div>
      <NuxtLink to="/" class="flex items-center justify-center">
        <img class="mb-8 w-32 xs:w-48 md:w-64" src="/Logo.png" alt="LOGO" />
      </NuxtLink>
      <p class="text-center">
        我们是一家专业的公司，专注于产品，应用和服务的控制和测试技术解决方案公司。
      </p>
      <div class="flex items-center justify-evenly mt-8">
        <a href="tel:021-51593021">
          <img class="aspect-square w-6" src="/Icons/Icon1.png" alt="" />
        </a>
        <a :href="mailTo">
          <img
            class="aspect-square w-6"
            src="/Icons/Icon2.png"
            alt="Email Icon"
          />
        </a>
        <a href="https://j.map.baidu.com/31/A8q">
          <img
            class="aspect-square w-6"
            src="/Icons/Icon3.png"
            alt="Email Icon"
          />
        </a>
      </div>
    </div>

    <hr />

    <div class="flex items-center justify-between py-8">
      <div class="text-center">
        <p>
          Copyright © 2024 minis-tech.com All Rights Reserved.
          上海明尼诗电子科技有限公司 版权所有
        </p>
      </div>
    </div>
  </footer>
</template>

<script setup>
const emailSubject = encodeURIComponent("我想要订购 MGC-1624");
const emailBody = encodeURIComponent("你好, Minis!\n我感兴趣");
const mailTo = `mailto:chuping.he@minis-tech.com?subject=${emailSubject}&body=${emailBody}`;
</script>

<style>
.flex {
  height: 100%;
}
</style>