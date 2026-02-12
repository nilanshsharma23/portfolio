<script lang="ts">
	import dateFormat from 'dateformat';
	import InteractionTemplate from './InteractionTemplate.svelte';

	let { date, content = null, likes = 0, comments = 0, imageSrc = null } = $props();
</script>

<div class="flex w-lg flex-col gap-4 border border-[#83C092] p-4">
	<div class="flex flex-row items-center gap-2">
		<img src="/pfp_transparent.png" alt="" class="h-12 w-12" />
		<div class="text-xl">Nilansh Sharma</div>
		<div class="text-xl text-[#7A8478]">
			{dateFormat(date, 'mediumDate')}
		</div>
	</div>
	{#if content}
		<div class="text-2xl">
			{content}
		</div>
	{/if}
	{#if imageSrc}
		<img src={imageSrc} class="w-full" alt="" />
	{/if}
	<div class="flex flex-row items-center justify-around">
		<InteractionTemplate icon="ri-thumb-up-line" count={likes} />
		<InteractionTemplate icon="ri-chat-4-line" count={comments} />
	</div>
</div>
