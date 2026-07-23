<script lang="ts">
	import campfire from '$lib/assets/campfire.webp';
	import space_channel from '$lib/assets/space_channel.png';
	import ss from '$lib/assets/ss.webp';
	import Atmosphere from '$lib/components/landing/Atmosphere.svelte';
	import Structure from '$lib/components/landing/Structure.svelte';
</script>

<div class="grid-layout">
	<img
		src={campfire}
		class="mt-4"
		alt="two folks sitting by campfire, one is playing instrument while other is enjoying sort of skewer."
	/>
</div>

<div class="grid-layout mt-10">
	<p>
		Humans are social animals. We crave bonding and social connections. In our digital worlds our
		common social space is campfire, which is <i>group chat</i>.
	</p>

	<p>It starts out something like this:</p>

	<img
		class="crispy"
		src={space_channel}
		alt="two sections with small section on left being 'space' and remaining space taken by 'channel' section."
	/>

	<p>That's roughly what it has looked like since the 90's.</p>

	<p>
		Roomy uses familiar structure, because we believe group chat is minimum viable everything. As
		it's the best default foundation for community building.
	</p>

	<img src={ss} class="rounded-md" alt="chat interface of roomy" />

	<Structure/>
	<Atmosphere/>
</div>
