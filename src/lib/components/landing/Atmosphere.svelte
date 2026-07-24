<script lang="ts">
	import Image from '$lib/components/Image.svelte';

	import data_platform from '$lib/assets/data_platform.png';
	import apps from '$lib/assets/apps.png';
	import group from '$lib/assets/group.png';
	import deer from '$lib/assets/deer.png';
</script>

<div class="grid-layout mt-8">
	<h2>Welcome to the Atmosphere</h2>

	<p>
		A better way to understand this is though a Camper. Camper is a travelling home vehicle that you
		can take anywhere. It provides you the freedom of living wherever you wish. Same is true for any
		app made on AT protocol.
	</p>

	<p>
		If you don't like it, you can always pack up and go somewhere else. But Big Tech doesn't like
		the idea. They want you to hand over the keys so they can decide where you settle.
	</p>

	<p>
		Ask any camper owner, the best thing about owning one is freedom. This freedom allows you to
		take part in anything you find interesting, and for <i>Roomy</i> that means a huge ecosystem of apps
		built on AT Protocol.
	</p>
</div>

<Image
	src={data_platform}
	class="cripsy mx-auto"
	alt="two groups, one is group of folks in a circle 'data' and other being 'platform' "
/>

<div class="grid-layout">
	<p>
		You always own your data. You choose a trusted location to settle it while being part of the
		community.
	</p>
</div>

<Image
	src={apps}
	class="cripsy mx-auto"
	alt="closed circles with famous social media apps, representing their nature of locking userdata at one place on their platform."
/>

<Image
	src={group}
	class="cripsy mx-auto"
	alt="open nature of at-protocol allowing many apps to coexist and share their data from a single source."
/>

<div class="grid-layout">
	<p>
		Roomy gives you a way to design your community while tinkering with apps you like from the
		ecosystem. Oh, and did we mention that you can use one account to use all of this?
	</p>
</div>
