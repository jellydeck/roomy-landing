<script lang="ts">
	import thoughts from '$lib/assets/thoughts.png';
	import threads from '$lib/assets/threads.png';
	import Image from '../Image.svelte';
</script>

<div class="grid-layout mt-8">
	<h2>In search of structure</h2>
	<p>
		The thing about group chat is that it wants conversation to keep moving. It's like a river,
		always trying to push forward. Structurally, old school forums just worked better for this
		reason. All of the relevant coversations were grouped together by topics and index board.
	</p>

	<p>
		Each conversation on forums is contained under a topic. This seemingly simple design choice
		curates info really nicely. Modern Discord is not meaningfully better at knowledge-management.
		For groups engaged in knowledge work, revisiting conversation is important.
	</p>

	<Image
		src={thoughts}
		class="crispy"
		alt="thought is born. which in turn end up as conversation which being chats. we can gather this into an coherent block as 'threads'. this in turn helps us to compile down into condensed shapes such as article."
	/>

	<p>
		When larger spaces of discourse grow more complex, Roomy's UI opens up gradually, keeping
		everything orderly. We can simply create a thread and keep chatting, as simple as that.
	</p>
</div>

<Image
	class="crispy"
	src={threads}
	caption="we're <i>proud</i> of this 🥹"
	alt="thread interface of roomy. a toggle at top allows quickly switch between chat and threads intuitively."
/>

<div class="grid-layout">
	<p>
		The best in the biz right now are Zulip and Discourse. Zulip is especially close to Roomy in its
		chat-to-threads approach.
	</p>

	<p>
		Where Roomy differs is in being an atmospheric web app, 'atmospheric' is adhering to the AT
		protocol.
	</p>
</div>
