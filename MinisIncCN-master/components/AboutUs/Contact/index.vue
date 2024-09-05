<template>
  <div class="container mx-auto py-16 -my-4">
    <h1 class="text-center text-5xl px-8 font-bold">如何联系我们？</h1>
    <div class="flex items-center justify-center">
      <div
        class="grid grid-cols-1 lg:grid-cols-3 mt-8 gap-y-8 gap-x-16 place-self-center"
      >
        <AboutUsContactCard
          img="Icons/Icon1.png"
          content="021-51593021"
          href="tel:021-51593021"
        />
        <AboutUsContactCard
          img="Icons/Icon2.png"
          content="chuping.he@minis-tech.com"
          :href="mailTo"
        />
        <AboutUsContactCard
          img="Icons/Icon3.png"
          content="上海市図行区虹梅南路4999弄22号楼东2楼"
          href="https://j.map.baidu.com/31/A8q"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
const emailSubject = encodeURIComponent("我想要订购 MGC-1624");
const emailBody = encodeURIComponent("你好, Minis!\n我感兴趣");
const mailTo = `mailto:chuping.he@minis-tech.com?subject=${emailSubject}&body=${emailBody}`;
</script>