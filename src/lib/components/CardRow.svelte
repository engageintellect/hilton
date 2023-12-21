<script lang="ts">
	export let name = 'Name';
	export let description = 'Description';
	export let type = 'Type';
	export let photo = 'Photo';
</script>

<div class="mx-auto h-full w-full max-w-5xl overflow-x-scroll">
	<div class="flex flex-row gap-2">
		<div class="relative h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div class="h-full w-full overflow-hidden rounded">
				<img
					src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxleHBsb3JlLWZlZWR8Mnx8fGVufDB8fHx8fA%3D%3D"
					alt={name}
					class="h-full w-full object-cover"
				/>
			</div>

			<div
				class="absolute inset-0 flex flex-col items-center justify-center text-center text-white opacity-0 transition-opacity duration-300 hover:opacity-100"
			>
				<div>{name}</div>
				<div>{description}</div>
				<div>{type}</div>
			</div>
		</div>

		<div class="relative h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div class="h-full w-full overflow-hidden rounded">
				<img
					src="https://t4.ftcdn.net/jpg/02/86/17/89/360_F_286178925_8zk89O9uC5JJVPvqhvBMUpaRxp8AFXzD.jpg"
					alt={name}
					class="h-full w-full object-cover"
				/>
			</div>

			<div
				class="absolute inset-0 flex flex-col items-center justify-center text-center text-white opacity-0 transition-opacity duration-300 hover:opacity-100"
			>
				<div>{name}</div>
				<div>{description}</div>
				<div>{type}</div>
			</div>
		</div>

		<div class="relative h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div class="h-full w-full overflow-hidden rounded">
				<img
					src="https://www.foodiesfeed.com/wp-content/uploads/2023/06/burger-with-melted-cheese.jpg"
					alt={name}
					class="h-full w-full object-cover"
				/>
			</div>

			<div
				class="absolute inset-0 flex flex-col items-center justify-center text-center text-white opacity-0 transition-opacity duration-300 hover:opacity-100"
			>
				<div>{name}</div>
				<div>{description}</div>
				<div>{type}</div>
			</div>
		</div>

		<div class="relative h-64 w-2/3 flex-shrink-0 rounded border p-2 shadow sm:w-1/3">
			<div class="h-full w-full overflow-hidden rounded">
				<img
					src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxleHBsb3JlLWZlZWR8Mnx8fGVufDB8fHx8fA%3D%3D"
					alt={name}
					class="h-full w-full object-cover"
				/>
			</div>

			<div
				class="absolute inset-0 flex flex-col items-center justify-center text-center text-white opacity-0 transition-opacity duration-300 hover:opacity-100"
			>
				<div>{name}</div>
				<div>{description}</div>
				<div>{type}</div>
			</div>
		</div>
	</div>
</div>
