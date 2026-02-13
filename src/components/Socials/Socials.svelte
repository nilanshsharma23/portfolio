<script lang="ts">
	import IconLinkTemplate from './IconLinkTemplate.svelte';
</script>

<div class="flex max-w-96 flex-col gap-4 p-4">
	<div class="flex flex-row items-center justify-center gap-2">
		<img src="/pfp_transparent.png" alt="" class="h-24 w-24" />
		<div class="text-4xl">Nilansh Sharma</div>
	</div>
	<div class="text-2xl">High school student who likes making games and apps that help society.</div>
	<div class="flex flex-row gap-4 text-2xl text-[#7A8478]">
		<i class="ri-map-pin-2-line"></i>
		<div>Noida, India</div>
	</div>
	<div class="flex flex-row gap-4 text-2xl text-[#7A8478]">
		<i class="ri-school-line"></i>
		<div>DPS Indirapuram</div>
	</div>
	<IconLinkTemplate icon="ri-github-line" link="https://github.com/nilanshsharma23" text="GitHub" />
	<IconLinkTemplate
		icon="ri-linkedin-fill"
		link="https://www.linkedin.com/in/nilansh-sharma-967b062a5/"
		text="LinkedIn"
	/>
	<IconLinkTemplate icon="ri-youtube-line" link="https://www.youtube.com/@pyscrap" text="YouTube" />
	<IconLinkTemplate
		icon="ri-google-play-line"
		link="https://play.google.com/store/apps/dev?id=5028805465809922357"
		text="Google Play"
	/>
</div>
