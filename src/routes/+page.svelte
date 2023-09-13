<script>
	import logo from '$lib/assets/logo.png';
</script>

<svelte:head>
	<script async src="https://cse.google.com/cse.js?cx=4057f0107f2b1450f"></script>
</svelte:head>

<body class="bg-mc-white absolute w-screen flex flex-col">
	<div class="flex justify-center py-3 md:py-20">
		<img class="w-2/3 md:w-1/3" alt="Modesty Concept logo" src={logo} />
	</div>
	<div class="flex justify-center">
		<div class="w-11/12 md:w-9/12">
			<div class="gcse-search" />
		</div>
	</div>
</body>
