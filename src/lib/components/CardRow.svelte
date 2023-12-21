<script lang="ts">
	export let name = 'Name';
	export let description = 'Description';
	export let type = 'Type';
	export let photo = 'Photo';
</script>

<div class="mx-auto h-full w-full max-w-5xl overflow-x-scroll p-2">
	<div class="flex flex-row gap-2">
		<div class="h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div>{name}</div>
			<div>{description}</div>
			<div>{type}</div>
			<div>{photo}</div>
		</div>

		<div class="h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div>{name}</div>
			<div>{description}</div>
			<div>{type}</div>
			<div>{photo}</div>
		</div>

		<div class="h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div>{name}</div>
			<div>{description}</div>
			<div>{type}</div>
			<div>{photo}</div>
		</div>

		<div class="h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div>{name}</div>
			<div>{description}</div>
			<div>{type}</div>
			<div>{photo}</div>
		</div>
	</div>
</div>
