<script>
	import { onMount } from "svelte";

	onMount(() => {
	  console.log("the component has mounted With Svelte");
	});
</script>

<main>
	<div class="container" style="margin-top: 100px;">
		<div class="row justify-content-center">
			<div class="col-md-8">
				<div class="card">
					<div class="card-header">
					 	<h2>Svelte Component</h2>
					 </div>
					<div class="card-body">
					<h4>
						I'm an example component from Svelte.
					</h4>
						
					</div>
				</div>
			</div>
		</div>
	</div>
</main>