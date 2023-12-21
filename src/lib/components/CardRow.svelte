<script lang="ts">
	export let name = 'Name';
	export let description = 'Description';
	export let price = 'Price';
	export let type = 'Type';
	export let imageURL = 'Image';
</script>

<!-- <div class="scroll-hide mx-auto h-full w-full max-w-5xl overflow-x-scroll"> -->
<!-- <div class="flex flex-row gap-2"> -->
<div class="relative h-64 w-2/3 flex-shrink-0 rounded border shadow sm:w-1/3">
	<div class="h-full w-full overflow-hidden rounded">
		<img src={imageURL} alt={imageURL} class="h-full w-full object-cover" />
	</div>

	<div
		class="absolute inset-0 flex flex-col items-center justify-center rounded bg-zinc-900/50 text-center text-white opacity-0 transition-opacity duration-300 hover:opacity-100"
	>
		<div class="font-bold drop-shadow">
			<div>{name}</div>
			<div>{description}</div>
			<div>{type}</div>
			<div>{price}</div>
		</div>
	</div>
	<!-- </div> -->
	<!-- </div> -->
</div>
