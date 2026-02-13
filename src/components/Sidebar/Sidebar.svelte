<script>
	import SidebarButton from './SidebarButton.svelte';
</script>

<div class="fixed hidden h-screen w-64 flex-col gap-2 bg-[#272E33] p-4 lg:flex">
	<div class="p-2 text-2xl">Not The Social Network</div>
	<SidebarButton icon="ri-home-4-line" text="Life" route="/" filledIcon="ri-home-4-fill" />
	<SidebarButton
		icon="ri-kanban-view"
		text="Projects"
		route="/projects"
		filledIcon="ri-kanban-view"
	/>
	<SidebarButton
		icon="ri-svelte-line"
		text="Tech Stack"
		route="/tech-stack"
		filledIcon="ri-svelte-fill"
	/>
</div>
