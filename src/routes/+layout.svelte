<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import 'remixicon/fonts/remixicon.css';
	import Sidebar from '../components/Sidebar/Sidebar.svelte';
	import BottomBar from '../components/BottomBar/BottomBar.svelte';
	import Socials from '../components/Socials/Socials.svelte';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href="/pfp_transparent.png" /></svelte:head>
<div class="flex w-full flex-col lg:flex-row">
	<Sidebar />
	{@render children()}
	<div class="fixed right-0 hidden xl:block">
		<Socials />
	</div>
	<BottomBar />
</div>
