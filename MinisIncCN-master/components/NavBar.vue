<template>
  <Disclosure as="nav" class="py-8" v-slot="{ open }">
    <div class="mx-auto container px-8">
      <div class="relative flex h-16 items-center justify-between">
        <div class="absolute inset-y-0 right-0 flex items-center md:hidden">
          <NuxtLink
            to="https://www.wenjuan.com/s/UZBZJvlmuC/"
            target="_blank"
            class="px-3 mr-4 py-2 bg-dark-blue text-white rounded-md"
            >我要订购!</NuxtLink
          >
          <!-- Mobile menu button-->
          <DisclosureButton
            class="relative inline-flex items-center justify-center rounded-md p-2 text-black hover:bg-dark-blue hover:scale-110 ease-in-out duration-100 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
          >
            <span class="absolute -inset-0.5" />
            <span class="sr-only">Open main menu</span>
            <Bars3Icon v-if="!open" class="block h-6 w-6" aria-hidden="true" />
            <XMarkIcon v-else class="block h-6 w-6" aria-hidden="true" />
          </DisclosureButton>
        </div>
        <div class="flex items-center justify-between w-full">
          <div class="flex items-center">
            <NuxtLink to="/">
              <img class="w-32 xs:w-48 md:w-64" src="/Logo.png" alt="LOGO" />
            </NuxtLink>
          </div>
          <div class="hidden md:block">
            <div class="flex items-center justify-between gap-10">
              <NuxtLink to="/" :class="{ 'font-bold': $route.path === '/' }"
                >首页</NuxtLink
              >
              <NuxtLink
                to="/product"
                :class="{ 'font-bold': $route.path === '/product' }"
                >产品目录</NuxtLink
              >
              <NuxtLink
                to="/about"
                :class="{ 'font-bold': $route.path === '/about' }"
                >关于我们</NuxtLink
              >
              <NuxtLink
                to="https://www.wenjuan.com/s/UZBZJvlmuC/"
                target="_blank"
                class="px-6 py-3 bg-dark-blue text-white rounded-md"
                >我要订购!</NuxtLink
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <DisclosurePanel class="md:hidden">
      <div class="mt-4">
        <div class="flex flex-col text-right px-8 justify-between -mb-8">
          <NuxtLink
            to="/"
            class="border-t-2 border-gray-300 w-full py-3 mt-4"
            :class="{ 'font-bold': $route.path === '/' }"
            >首页</NuxtLink
          >
          <NuxtLink
            to="/product"
            class="border-t-2 border-gray-300 w-full py-3"
            :class="{ 'font-bold': $route.path === '/product' }"
            >产品目录</NuxtLink
          >
          <NuxtLink
            to="/about"
            class="border-t-2 border-gray-300 w-full py-3"
            :class="{ 'font-bold': $route.path === '/about' }"
            >关于我们</NuxtLink
          >
        </div>
      </div>
    </DisclosurePanel>
  </Disclosure>
</template>

<script setup>
import {
  Disclosure,
  DisclosureButton,
  DisclosurePanel,
  Menu,
  MenuButton,
  MenuItem,
  MenuItems,
} from "@headlessui/vue";
import { Bars3Icon, BellIcon, XMarkIcon } from "@heroicons/vue/24/outline";
</script>