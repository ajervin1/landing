<template>
	<section class="features py-5">
		<div class="container">
			<div class="features-top text-center mb-5">
				<h2>How It Works</h2>
			</div>
			<div class="row">
				<div class="col-4 text-center" v-for="x in 3">
					<article class="card">
				
						<div class="card-body">
							<img src="https://hviorder.ca/img/track.svg" class="w-25 mb-3">
							<p class="text-body">
								On our mobile friendly web portal, you can track the status of your
								active appraisal orders with HVI. You’ll have access to contact
								information for your assigned appraiser, as well as the assignment
								progress details including the ETD (Estimated Time of Delivery) of
								your
								property appraisal report.
							</p>
						</div>
					
					</article>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Features',
		data () {
			return {}
		}
	}
</script>
