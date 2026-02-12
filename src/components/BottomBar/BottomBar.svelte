<script lang="ts">
	import BottomBarButton from './BottomBarButton.svelte';
</script>

<div
	class="fixed bottom-0 flex w-screen flex-row items-center justify-around bg-[#272E33] p-4 lg:hidden"
>
	<BottomBarButton icon="ri-home-4-line" filledIcon="ri-home-4-fill" route="/" text="Life" />
	<BottomBarButton
		icon="ri-kanban-view"
		filledIcon="ri-kanban-view"
		route="/projects"
		text="Projects"
	/>
	<BottomBarButton
		icon="ri-svelte-line"
		filledIcon="ri-svelte-fill"
		route="/tech-stack"
		text="Tech Stack"
	/>
	<BottomBarButton icon="ri-hashtag" filledIcon="ri-hashtag" route="/socials" text="Socials" />
</div>
