<script>
	import logo from '$lib/assets/logo.png';
</script>

<svelte:head>
	<script async src="https://cse.google.com/cse.js?cx=4057f0107f2b1450f"></script>
</svelte:head>

<div class="bg-mc-white absolute w-full h-full flex flex-col">
	<div class="flex justify-center py-20">
		<img class="w-1/3" alt="Modesty Concept logo" src={logo} />
	</div>
	<div class="flex justify-center">
		<div class="w-9/12">
			<div class="gcse-search" />
		</div>
	</div>
</div>
