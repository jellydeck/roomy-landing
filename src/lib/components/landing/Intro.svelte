<script lang="ts">
	import space_channel from '$lib/assets/space_channel.png';
	import ss from '$lib/assets/ss.png';
	import Image from '../Image.svelte';
</script>

<div class="grid-layout mt-10">
	<p>
		Humans are social creatures. We crave bonding and social connections. In our digital world, our
		common social space is campfire, which is the <i>group chat</i>.
	</p>

	<p>It starts out something like this:</p>
</div>

<Image
	src={space_channel}
	class="crispy mx-auto"
	alt="two sections with small section on left being 'space' and remaining space taken by 'channel' section."
/>

<div class="grid-layout">
	<p>That's roughly what it has looked like since the 90's.</p>

	<p>
		Roomy uses familiar structure, because we believe group chat is minimum viable everything. As
		it's the best default foundation for community building.
	</p>
</div>

<Image
	src={ss}
	class="crispy"
	caption="Building for and <i>with</i> communities."
	alt="chat interface of roomy"
/>
