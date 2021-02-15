<script>
	export let name;
</script>

<main>
	<div class="Header">
		<div class="Header_container">
			<div class="Header_container-logo">
				<figure>
					<img src="https://s3.amazonaws.com/gndx.dev/gndx.png" alt="Oscar Barajas @gndx">
				</figure>
			</div>
			<div class="Header_container_nav">
				<ul>
					<li>Element</li>
				</ul>
			</div>
		</div>
	</div>
	<div class="Calendar">
		<div class="Calendar_container">
			<h2>Calendar</h2>
		</div>
	</div>
	<div class="Footer">
		<div class="Footer_container">
			
		</div>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
