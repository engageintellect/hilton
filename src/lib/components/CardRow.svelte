<script lang="ts">
	export let name = 'Name';
	export let description = 'Description';
	export let price = 'Price';
	export let type = 'Type';
	export let imageURL = 'Image';
	export let menuURL = 'Menu';
</script>

<div class="relative h-64 w-2/3 flex-shrink-0 cursor-pointer rounded border shadow sm:w-[300px]">
	<a target="_blank" href={menuURL}>
		<div class="h-full w-full overflow-hidden rounded">
			<img src={imageURL} alt={imageURL} class="h-full w-full object-cover" />
		</div>

		<div
			class="absolute inset-0 flex flex-col items-center justify-center rounded bg-zinc-900/60 text-center text-white transition-opacity duration-300 sm:opacity-0 sm:hover:opacity-100"
		>
			<div class="p-2 font-bold drop-shadow">
				<div>{name}</div>
				<div class="text-sm font-thin">{description}</div>
				<div>{type}</div>
				<div>{price}</div>
			</div>
		</div>
	</a>
</div>
