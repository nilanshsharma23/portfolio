<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import Sidebar from '../components/Sidebar/Sidebar.svelte';
	import 'remixicon/fonts/remixicon.css';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<div class="flex w-full flex-row">
	<Sidebar />
	<div>
		{@render children()}
	</div>
</div>
