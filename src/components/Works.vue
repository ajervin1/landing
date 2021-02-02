<template>
	<section class="works py-5 bg-secondary">
		<div class="container">
			<div class="works-top mb-5">
				<h2 class="text-center">How It Works</h2>
			</div>
			<!--Work Items-->
			<div class="row">
				<div class="col-12 col-md-4 text-center" v-for="x in 3">
					<article class="text-center">
						<img src="https://hviorder.ca/img/map.svg" class="">
						<h2>Check Coverage</h2>
						<p>HVI has professional residential appraisers throughout the GTA. We service
							Toronto, Peel, York Region, Durham, and Halton. See the coverage map above,
							to get a sense for the breadth of our service provision.</p>
					</article>
				
				</div>
			</div>
		
		
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Works',
		data () {
			return {}
		}
	}
</script>
