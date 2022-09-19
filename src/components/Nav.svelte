<script>
	import logo from '/static/logos/hsmirae-text.svg'
</script>

<header class="p-2 text-bg-yellow">
	<div class="container">
		<div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
			<a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
				<!-- <span class="nav-logo" style="font-family: noto-sans-cjk-kr, sans-serif; color: black;">HSMIRAE</span> -->
				<img src="{ logo }" class="nav-logo" alt="">
			</a>

			<ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
				<li><a href="#" class="nav-link px-2 text-secondary">Home</a></li>
				<!-- <li><a href="#" class="nav-link px-2 text-dark">Features</a></li>
				<li><a href="#" class="nav-link px-2 text-dark">Product</a></li>
				<li><a href="#" class="nav-link px-2 text-dark">Contact Us</a></li> -->
			</ul>
		</div>
	</div>
</header>

<style lang="scss">
	.text-bg-yellow {
    color: #fff!important;
    // background-color: RGBA(33,37,41,var(--bs-bg-opacity,1))!important
		background-color: #ffdd00!important;
	}

	.nav-logo {
		height: 50px;
	}
</style>
