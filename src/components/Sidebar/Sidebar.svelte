<script>
	import SidebarButton from './SidebarButton.svelte';
</script>

<div class="fixed flex h-screen w-64 flex-col gap-2 bg-[#272E33] p-4">
	<div class="p-2 text-2xl">Not The Social Network</div>
	<SidebarButton icon="ri-news-line" text="About" route="/" filledIcon="ri-news-fill" />
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
	<SidebarButton icon="ri-hashtag" text="Socials" route="/socials" filledIcon="ri-hashtag" />
</div>
