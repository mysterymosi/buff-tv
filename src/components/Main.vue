<template>
    <div id="main">
        <!-- <TheHeader /> -->
        <router-view />
        <VueInjectJs src="/landing/js/vendor/popper.min.js" />
        <VueInjectJs src="/landing/js/jquery.easing.1.3.js" />
        <VueInjectJs src="/landing/js/vendor/bootstrap.min.js" />
        <VueInjectJs src="/landing/js/jquery.parallax-scroll.js" />
        <VueInjectJs src="/landing/js/owl.carousel.min.js" />
        <VueInjectJs src="/landing/js/waypoints.min.js" />
        <VueInjectJs src="/landing/js/jquery.stellar.min.js" />
        <VueInjectJs src="/landing/js/main.js" />
    </div>
</template>

<script>
import VueInjectJs from "vue-inject-js";
// import TheHeader from "@/components/TheHeader.vue";
export default {
	components: {
		VueInjectJs
		// TheHeader
	}
}
</script>
