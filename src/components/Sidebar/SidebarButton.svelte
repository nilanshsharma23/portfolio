<script lang="ts">
	import { page } from '$app/state';

	let { icon, text, route, filledIcon } = $props();
</script>

{#if page.url.pathname != route}
	<a
		href={route}
		class="flex cursor-pointer flex-row gap-2 rounded-xl p-2 text-xl hover:bg-[#2E383C]"
	>
		<i class={icon}></i>
		<div class="w-full text-[#D3C6AA]">{text}</div>
	</a>
{:else}
	<div class="flex cursor-pointer flex-row gap-2 rounded-xl bg-[#DBBC7F] p-2 text-xl">
		<i class="{filledIcon} text-[#1E2326]"></i>
		<div class="w-full text-[#1E2326]">{text}</div>
	</div>
{/if}
