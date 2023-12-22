<script lang="ts">
	export let name = 'Name';
	export let description = 'Description';
	export let price = 'Price';
	export let type = 'Type';
	export let imageURL = 'Image';
	export let menuURL = '';
</script>

<div
	class="group relative my-5 w-2/3 flex-shrink-0 cursor-pointer rounded bg-white shadow sm:w-[300px]"
>
	<img src={imageURL} alt="" class="h-32 w-full rounded-t object-cover sm:h-48 md:h-52" />

	{#if menuURL}
		<div class="absolute left-0 top-0 p-2">
			<a target="_blank" href={menuURL}>
				<button class="rounded bg-white px-4 py-2 text-sm uppercase shadow">Menu</button>
			</a>
		</div>
	{/if}
	<div class="  p-2">
		<div class="font-semibold">{name}</div>
		<div class="text-sm font-thin">{description}</div>
	</div>
</div>

<!-- 
<div class="relative w-2/3 flex-shrink-0 cursor-pointer rounded border shadow sm:w-[300px]">
	<a target="_blank" href={menuURL}>
		<div class="h-full w-full overflow-hidden rounded">
			<img src={imageURL} alt={imageURL} class="h-full w-full object-cover" />
		</div>

		<div
			class="absolute inset-0 flex flex-col rounded bg-zinc-900/60 text-white transition-opacity duration-300 sm:opacity-0 sm:hover:opacity-100"
		>
			<div class="p-2 font-bold drop-shadow">
				<div>{name}</div>
				<div class="text-sm font-thin">{description}</div>
				<div>{type}</div>
				<div>{price}</div>
			</div>
		</div>
	</a>
</div> -->
