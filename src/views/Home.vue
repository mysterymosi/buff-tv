<template>
  <div>
    <TheHeader />
    <Banner />
    <WhyBuff />
    <GetBuff />
    <Partners />
    <FAQs />
  </div>
</template>

<script>
// @ is an alias to /src
import TheHeader from "@/components/TheHeader.vue";
import Banner from "@/components/Banner.vue";
import WhyBuff from "@/components/WhyBuff.vue";
import GetBuff from "@/components/GetBuff.vue";
import Partners from "@/components/Partners.vue";
import FAQs from "@/components/FAQs.vue";

export default {
  name: "Home",
  components: {
    TheHeader,
    Banner,
    WhyBuff,
    GetBuff,
    Partners,
    FAQs
  }
};
</script>
