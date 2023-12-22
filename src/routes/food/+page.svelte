<script lang="ts">
	import CardRow from '$lib/components/CardRow.svelte';

	import { allFood } from '$lib/data/food';
</script>

<div class="mx-auto w-full max-w-5xl p-2 py-10">
	<div class="text-center text-5xl font-bold">Food</div>

	<!-- <div class="my-10" id="all-food">
		<div class="">
			<a href="#all-food" class="rounded bg-black p-2 text-lg font-semibold uppercase text-white"
				>All Food</a
			>
			<div class="my-2 font-thin">
				Nostrud et aute sunt ea sint sint sint elit nisi labore. Laboris nisi Lorem adipisicing
				enim. Incididunt anim nostrud ut qui nulla eiusmod voluptate sit enim fugiat aute duis.
			</div>
		</div>

		<div class="scroll-hide mx-auto h-full w-full max-w-5xl overflow-x-scroll">
			<div class="flex flex-row gap-2">
				{#each allFood as food}
					<CardRow
						name={food.name}
						type={food.type}
						price={food.price}
						imageURL={food.imageURL}
						description={food.description}
						menuURL={food.menuURL}
					/>
				{/each}
			</div>
		</div>
	</div> -->

	<div class="my-10" id="resturaunts">
		<div class="">
			<a href="#resturaunts" class="rounded bg-black p-2 text-lg font-semibold uppercase text-white"
				>Resturaunts</a
			>
			<div class="my-2 font-thin">
				Nostrud et aute sunt ea sint sint sint elit nisi labore. Laboris nisi Lorem adipisicing
				enim. Incididunt anim nostrud ut qui nulla eiusmod voluptate sit enim fugiat aute duis.
			</div>
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
							menuURL={food.menuURL}
						/>
					{/if}
				{/each}
			</div>
		</div>
	</div>

	<div class="my-10" id="bars">
		<div class="">
			<a href="#bars" class="rounded bg-black p-2 text-lg font-semibold uppercase text-white"
				>Bars</a
			>
			<div class="my-2 font-thin">
				Nostrud et aute sunt ea sint sint sint elit nisi labore. Laboris nisi Lorem adipisicing
				enim. Incididunt anim nostrud ut qui nulla eiusmod voluptate sit enim fugiat aute duis.
			</div>
		</div>

		<div class="scroll-hide mx-auto h-full w-full max-w-5xl overflow-x-scroll">
			<div class="flex flex-row gap-2">
				{#each allFood as food}
					{#if food.type == 'bar'}
						<CardRow
							name={food.name}
							type={food.type}
							price={food.price}
							imageURL={food.imageURL}
							description={food.description}
							menuURL={food.menuURL}
						/>
					{/if}
				{/each}
			</div>
		</div>
	</div>

	<div class="my-10" id="groceries">
		<div class="">
			<a href="#groceries" class="rounded bg-black p-2 text-lg font-semibold uppercase text-white"
				>Groceries</a
			>

			<div class="my-2 font-thin">
				Nostrud et aute sunt ea sint sint sint elit nisi labore. Laboris nisi Lorem adipisicing
				enim. Incididunt anim nostrud ut qui nulla eiusmod voluptate sit enim fugiat aute duis.
				Proident aliquip Lorem officia minim commodo cupidatat laborum. Ullamco laboris voluptate
				ipsum ea. Quis quis est consectetur aliqua.
			</div>
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
							menuURL={food.menuURL}
						/>
					{/if}
				{/each}
			</div>
		</div>
	</div>
</div>
