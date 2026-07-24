<script lang="ts">
	import Image from '$lib/components/ui/Image.svelte';

	import data_platform from '$lib/assets/data_platform.png';
	import apps from '$lib/assets/apps.png';
	import group from '$lib/assets/group.png';
</script>

<div class="grid-layout mt-8">
	<h2>Welcome to the Atmosphere</h2>

	<p>
		A better way to understand this is how Big Tech handles our data. All of our data is tighly
		coupled to the platform.
	</p>
</div>

<Image
	src={apps}
	class="cripsy mx-auto"
	alt="closed circles with famous social media apps, representing their nature of locking userdata at one place on their platform."
/>

<div class="grid-layout">
	<p>
		Now, imagine you stopped using twitter(X) and moved to a different app. It has all of your
		posts, pictures and followers. that would be amazing, No?
	</p>
</div>

<Image
	src={data_platform}
	class="cripsy mx-auto"
	alt="two groups, one is group of folks in a circle 'data' and other being 'platform' "
/>

<div class="grid-layout">
	<p>
		That's exactly what you can do using Bluesky, an atproto alternative to twitter(X) with 45
		Million users.
	</p>

	<p>
		This is where Roomy is positioning itself as an atproto app. An huge ecosystem that complements
		each other without enforcing users to one platform.
	</p>
</div>

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
