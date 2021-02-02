<template>
	<section class="sign-up bg-secondary py-10">
		<form class="card w-50 mx-auto">
			<div class="card-header">
				<h1>Create Account</h1>
			</div>
			<div class="card-body">
				
				<div class="mb-3">
					<input type="text" class="form-control" placeholder="Email">
				</div>
				<div class="mb-3">
					<input type="text" class="form-control" placeholder="Password">
				</div>
				<div class="">
					<button class="btn btn-primary">Sign Up</button>
				</div>
			
			</div>
		</form>
	</section>
</template>

<script>
	export default {
		name: 'SignUp',
		data () {
			return {}
		}
	}
</script>
