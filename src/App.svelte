<script lang="ts">

</script>

<main>
	<!-- <img src="/assets/images/hs_logo.png" alt="hs mirae" class="logo"> -->
	<!-- <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p> -->

	<div class="hsmirae-header">
		<h1>HS Mirae</h1>
		<p>Open the future of IT. Connect Anytime, anywhere.</p>
	</div>

	<div class="hsmirae-navigation-wrap">
		<ul>
			<li><header>Business</header></li>
			<li>Reservation System</li>
			<li>Scuba Diving Equipments</li>
		</ul>
	</div>
</main>

<style lang="scss">
	.hsmirae-header {
		// background-image: url(/assets/images/work-from-home-job-picjumbo-com.jpg);
		// background-repeat: no-repeat;
		// background-size: 100%;
		// background-position: left top;
		width: 100%;
		margin: 0;
		padding: 1em 0;
	}

	.hsmirae-navigation-wrap {
		font-weight: 200;

		ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
		}

		li + li {
			margin-top: 10px;
		}
	}

	main {
		text-align: center;
		padding: 1em;
		max-width: 400px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 109;
	}

	p {
		font-weight: 240;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>