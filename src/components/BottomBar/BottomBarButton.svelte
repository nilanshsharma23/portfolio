<script lang="ts">
	import { page } from '$app/state';

	let { route = '/', icon, filledIcon, text } = $props();
</script>

{#if page.url.pathname != route}
	<a href={route}>
		<div class="flex flex-col items-center justify-center pr-4 pl-4">
			<i class="{icon} text-3xl"></i>
			<div class="text-md text-center">{text}</div>
		</div>
	</a>
{:else}
	<a href={route}>
		<div class="flex flex-col items-center justify-center rounded-xl bg-[#DBBC7F] pr-4 pl-4">
			<i class="{filledIcon} text-3xl text-[#1E2326]"></i>
			<div class="text-md text-center text-[#1E2326]">{text}</div>
		</div>
	</a>
{/if}
