<script>
	import logo from '../assets/logos/HSMIRAE_LOGO_white_nobg.png'
</script>

<header class="p-2 text-bg-yellow">
	<div class="container">
		<div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
			<a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
				<img src="{ logo }" class="nav-logo" alt="">
			</a>

			<ul class="nav nav-custom col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
				<li><a href="#" class="nav-link px-2 text-secondary">Home</a></li>
				<li><a href="#" class="nav-link px-2 text-dark">Features</a></li>
				<li><a href="#" class="nav-link px-2 text-dark">Product</a></li>
				<li><a href="#" class="nav-link px-2 text-dark">Contact Us</a></li>
			</ul>
		</div>
	</div>
</header>

<style lang="scss">
	.nav-custom {
		padding-left: revert;
	}

	.text-bg-yellow {
    color: #fff!important;
    // background-color: RGBA(33,37,41,var(--bs-bg-opacity,1))!important
		background-color: #ffdd00!important;
	}

	.nav-logo {
		height: 80px;
	}
</style>
