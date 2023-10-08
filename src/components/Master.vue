<template>
    	<Header></Header>
	<!--================ End Header Area =================-->

	<RouterView></RouterView>
	<!--================ Start Newsletter Area =================-->
	<Newsletter></Newsletter>
	<!--================ End Newsletter Area =================-->

	<!--================Footer Area =================-->
	<Footer></Footer>
	<!--================End Footer Area =================-->

</template>
 
<script>
import Footer from './forntend/Footer.vue';
import Header from './forntend/Header.vue';
import Newsletter from './forntend/Newsletter.vue';

export default {
	name: "Master",
    components: { Header, Footer,Newsletter }
}
</script>

        Newsletter
<style>

</style>