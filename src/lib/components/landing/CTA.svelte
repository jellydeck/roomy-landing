<script lang="ts">
	import Image from '$lib/components/Image.svelte';

	import deer from '$lib/assets/deer.png';
	import Button from '../Button.svelte';
</script>

<div class="grid-layout">
	<Button href="https://roomy.space" class="w-full py-3 mt-8 no-underline">Launch Roomy</Button>
</div>
<Image src={deer} class="mx-auto no-margin translate-y-1" alt="deer " />
