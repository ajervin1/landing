<template>
	<section class="sign-up bg-secondary py-10">
		<form class="card w-50 mx-auto">
			<div class="card-header">
				<h1>Sign In</h1>
				<p>Please login with your email/username and password</p>
			</div>
			<div class="card-body">
				<div class="mb-3">
					<div class="input-group">
						<div class="input-group-prepend">
								<span class="input-group-text">
									<i class="fa fa-user"></i>
								</span>
						</div>
						<input type="text" class="form-control" placeholder="Email">
					</div>
				
				</div>
				<div class="mb-3">
					<div class="input-group">
						<div class="input-group-prepend">
								<span class="input-group-text">
									<i class="fa fa-key"></i>
								</span>
						</div>
						<input type="text" class="form-control" placeholder="Email">
					</div>
				
				</div>
			
			</div>
			<div class="card-footer d-flex justify-content-between align-items-center">
				<div class="left d-flex">
					
					<input type="checkbox" class="mb-1 mr-1"  />
					<label class="">
						Keep Me Signed In
					</label>
				</div>
				<div class="right">
					<button class="btn btn-primary">Login</button>
				</div>
			</div>
		</form>
	</section>
</template>

<script>
	export default {
		name: 'Login',
		data () {
			return {}
		}
	}
</script>
