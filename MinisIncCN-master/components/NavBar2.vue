<template>
  <nav class="flex items-center justify-between px-8 py-12 container mx-auto">
    <div class="">
      <NuxtLink to="/">
        <img class="w-64" src="/Logo.png" alt="LOGO" />
      </NuxtLink>
    </div>
    <div class="flex items-center justify-between gap-10">
      <NuxtLink to="/" :class="{ 'font-bold': $route.path === '/' }"
        >Home</NuxtLink
      >
      <NuxtLink
        to="/product"
        :class="{ 'font-bold': $route.path === '/product' }"
        >Our Products</NuxtLink
      >
      <NuxtLink to="/about" :class="{ 'font-bold': $route.path === '/about' }"
        >About Us</NuxtLink
      >
      <NuxtLink to="/" class="px-6 py-3 bg-dark-blue text-white rounded-md"
        >I want to Order!</NuxtLink
      >
    </div>
  </nav>
</template>

<script setup>
</script>
