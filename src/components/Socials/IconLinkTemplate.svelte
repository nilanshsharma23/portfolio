<script lang="ts">
	let { text, link, icon } = $props();
</script>

<a
	href={link}
	target="_blank"
	rel="noopener noreferrer"
	class="flex flex-row gap-4 text-2xl text-[#7A8478] hover:text-[#d3c6aa]"
>
	<i class={icon}></i>
	<div>{text}</div>
	<i class="ri-external-link-line"></i>
</a>
