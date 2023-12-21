<script lang="ts">
	import CardRow from '$lib/components/CardRow.svelte';
</script>

<div class="mx-auto my-10 w-full max-w-5xl p-2">
	<div class="text-center text-5xl font-bold">Food</div>

	<div class="my-5" id="resturaunts">
		<div class="text-lg font-bold uppercase">
			<a href="#resturaunts">Resturaunts</a>
		</div>
		<div>
			<CardRow />
		</div>
	</div>

	<div class="my-5" id="snacks">
		<div class="text-lg font-bold uppercase">
			<a href="#snacks">Snacks</a>
		</div>
		<div>
			<CardRow />
		</div>
	</div>

	<div class="my-5" id="groceries">
		<div class="text-lg font-bold uppercase">
			<a href="#groceries">Groceries</a>
		</div>
		<div>
			<CardRow />
		</div>
	</div>
</div>
