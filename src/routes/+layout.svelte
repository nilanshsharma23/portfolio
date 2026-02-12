<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import 'remixicon/fonts/remixicon.css';
	import Sidebar from '../components/Sidebar/Sidebar.svelte';
	import BottomBar from '../components/BottomBar/BottomBar.svelte';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<div class="flex w-full flex-col lg:flex-row">
	<Sidebar />
	{@render children()}
	<BottomBar />
</div>
