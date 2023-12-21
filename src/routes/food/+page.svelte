<script lang="ts">
	import CardRow from '$lib/components/CardRow.svelte';

	import { allFood } from '$lib/data/food';
</script>

<div class="mx-auto my-10 w-full max-w-5xl p-2">
	<div class="text-center text-5xl font-bold">Food</div>

	<!-- <div>{JSON.stringify(allFood)}</div> -->

	<div class="my-10" id="resturaunts">
		<div class="text-lg font-bold uppercase">
			<a href="#resturaunts">All Resturaunts</a>
		</div>

		<div class="scroll-hide mx-auto h-full w-full max-w-5xl overflow-x-scroll">
			<div class="flex flex-row gap-2">
				{#each allFood as food}
					{#if food.type == 'resturaunt'}
						<CardRow
							name={food.name}
							type={food.type}
							price={food.price}
							imageURL={food.imageURL}
							description={food.description}
						/>
					{/if}
				{/each}
			</div>
		</div>
	</div>

	<div class="my-10" id="snacks">
		<div class="text-lg font-bold uppercase">
			<a href="#snacks">Snacks</a>
		</div>

		<div class="scroll-hide mx-auto h-full w-full max-w-5xl overflow-x-scroll">
			<div class="flex flex-row gap-2">
				{#each allFood as food}
					{#if food.type == 'snacks'}
						<CardRow
							name={food.name}
							type={food.type}
							price={food.price}
							imageURL={food.imageURL}
							description={food.description}
						/>
					{/if}
				{/each}
			</div>
		</div>
	</div>

	<div class="my-10" id="groceries">
		<div class="text-lg font-bold uppercase">
			<a href="#groceries">Groceries</a>
		</div>
		<div class="scroll-hide mx-auto h-full w-full max-w-5xl overflow-x-scroll">
			<div class="flex flex-row gap-2">
				{#each allFood as food}
					{#if food.type == 'groceries'}
						<CardRow
							name={food.name}
							type={food.type}
							price={food.price}
							imageURL={food.imageURL}
							description={food.description}
						/>
					{/if}
				{/each}
			</div>
		</div>
	</div>
</div>
