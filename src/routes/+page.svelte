<script lang="ts">
	import campfire from '$lib/assets/campfire.webp';

	import Atmosphere from '$lib/components/landing/Atmosphere.svelte';
	import Intro from '$lib/components/landing/Intro.svelte';
	import Structure from '$lib/components/landing/Structure.svelte';
</script>

<div class="grid-layout">
	<img
		src={campfire}
		class="mt-4"
		alt="two folks sitting by campfire, one is playing instrument while other is enjoying sort of skewer."
	/>
</div>

<Intro />
<Structure />
<Atmosphere />
