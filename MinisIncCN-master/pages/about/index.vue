<template>
  <div>
    <Banner bannerImage="AboutUs/Gambar1.png" />
    <!-- <Slogan
      title="What are We?"
      content="We are a professional company focusing on products, applications and
        services of control and testing technology solutions company. After
        years of research, MGC-1624, which is leading in China and has the
        international advanced level, has been completed. The research and
        development of the new controller has been successfully launched. The
        company will keep abreast of market demand, adhere to continuous
        technological innovation, and develop more and better new products.
        Products, grow together with customers and industries."
    /> -->
    <Slogan
      title="我们是什么？"
      content="我们是一家专业的公司，专注于产品，应用和服务的控制和测试技术解决方案公司。 经过多年的研究，新的控制器MGC-1624已成功推出。 该产品代表了一个革命性的突破，有望推动行业向前发展。 公司将紧跟市场需求，坚持不断的技术创新，开发更多更好的新产品。"
    />
    <!-- <div class="">
      <Banner bannerImage="AboutUs/Gambar2.png" />
    </div> -->
    <img
      class="lg:container lg:mx-auto w-full xs:px-12 pt-16"
      src="/AboutUs/Gambar2.png"
      alt=""
    />
    <AboutUsThirdParty />
    <AboutUsContact />
    <HomeMaps />
  </div>
</template>

<script setup>
definePageMeta({
  layout: "default",
  head: {
    title: "About Us - Minis.Inc",
  },
});
onMounted(() => {
  document.title = "About Us - Minis.Inc";
});
</script>