<template>
	<div id="app" class="">
		<NavBar/>
		<Hero/>
		<Works/>
		<Features/>
		<Mobile />
		<Testimonials />
		<Appraisal />
		<Footer />
	</div>
</template>

<script>
	
	
	
	import Mobile from './components/Mobile'
	import NavBar from './components/NavBar'
	import Hero from './components/Hero'
	import Works from './components/Works'
	import Features from './components/Features'
	import Testimonials from './components/Testimonials'
	import Appraisal from './components/Appraisal'
	import Footer from './components/Footer'
	
	export default {
		name: 'App',
		components: { Footer, Appraisal, Testimonials, Features, Works, Hero, NavBar, Mobile },
	}
</script>

<style lang="scss">
	.bg-image {
		background: url("https://cartzilla.createx.studio/img/components/jumbotron/jumbotron-bg.jpg");
		background-size: cover;
		background-position: center;
	}
</style>
