<script lang="ts">
	export let eventName = '';
	export let eventDescription = '';
	export let eventDate = '';
	export let eventTime = '';
	export let eventImage = '';
</script>

<div class="w-full rounded bg-purple-500 shadow">
	<div class="flex w-full">
		<div class="w-full text-white">
			<div class="flex h-full flex-col gap-2 text-xs">
				<div class="row flex w-full gap-5 rounded-tl bg-purple-700 p-2 shadow">
					<div class="font-thin">{eventDate || 'Event Date'}</div>
					<div>{eventTime || 'Event Time'}</div>
				</div>

				<div class="flex flex-col px-2 pb-2">
					<div class="text-lg font-bold">{eventName || 'Event Name'}</div>
					<div class="text-xs">{eventDescription || 'Event Description'}</div>
				</div>

				<div class="flex gap-2 p-2">
					<button class="rounded bg-purple-700 px-4 py-2 font-bold uppercase shadow">+</button>
				</div>
			</div>
		</div>

		<div class="rounded-r-500 flex w-full">
			<img class="h-full rounded-r object-cover" src={eventImage} alt="event" />
		</div>
	</div>
</div>
