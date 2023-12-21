<script lang="ts">
	import CardRow from '$lib/components/CardRow.svelte';
</script>

<div class="mx-auto my-10 w-full max-w-5xl">
	<div class="text-center text-5xl font-bold">Food</div>

	<div class="my-5">
		<div class="text-lg font-bold uppercase">Resturants</div>
		<div>
			<CardRow />
		</div>
	</div>

	<div class="my-5">
		<div class="text-lg font-bold uppercase">Snacks</div>
		<div>
			<CardRow />
		</div>
	</div>

	<div class="my-5">
		<div class="text-lg font-bold uppercase">Desserts</div>
		<div>
			<CardRow />
		</div>
	</div>

	<div class="my-5">
		<div class="text-lg font-bold uppercase">Groceries</div>
		<div>
			<CardRow />
		</div>
	</div>
</div>
