<script lang="ts">
	import Image from '$lib/components/ui/Image.svelte';

	import Atmosphere from '$lib/components/landing/Atmosphere.svelte';
	import Intro from '$lib/components/landing/Intro.svelte';
	import Structure from '$lib/components/landing/Structure.svelte';
	import CTA from '$lib/components/landing/CTA.svelte';

	import campfire from '$lib/assets/computer_lady.png';
</script>

<div class="grid-layout">
	<Image
		src={campfire}
		class="crispy mt-4"
		alt="two folks sitting by campfire, one is playing instrument while other is enjoying sort of skewer."
	/>
</div>

<Intro />
<Structure />
<Atmosphere />
<CTA/>
