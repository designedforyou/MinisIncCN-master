<template>
  <div
    class="grid grid-rows-3 place-items-center bg-white rounded-xl shadow-md shadow-black p-8"
  >
    <img class="w-32 h-32 object-cover" :src="image" :alt="image" />
    <h1 class="text-2xl font-bold text-center">{{ title }}</h1>
    <p class="text-center">
      {{ description }}
    </p>
  </div>
</template>

<script setup>
const props = defineProps({
  title: {
    type: String,
    default: "Service Name",
  },
  description: {
    type: String,
    default:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis ullam aperiam laborum voluptatum eveniet architecto, alias fuga repellat! Aliquid fugiat voluptatibus labore deleniti veritatis, in dicta eos sit exercitationem ipsum.",
  },
  image: {
    type: String,
    default: "https://cdn-icons-png.flaticon.com/128/1067/1067566.png",
  },
});
</script>
