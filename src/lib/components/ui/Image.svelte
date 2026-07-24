<script lang="ts">
	import type { Picture } from '@sveltejs/enhanced-img';
	import type { ClassValue } from 'svelte/elements';

	const {
		src,
		alt,
		caption,
		class: className
	} = $props<{
		src: string | Picture;
		alt: string;
		caption?: string;
		class?: ClassValue;
	}>();
</script>

<figure>
	<enhanced:img {src} {alt} class={className} />

	{#if caption}
		<figcaption>
			<!-- eslint-disable svelte/no-at-html-tags -->
			<!-- manually provided-->
			{@html caption}
		</figcaption>
	{/if}
</figure>
