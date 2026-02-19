<script lang="ts">
	let { icon } = $props();
</script>

<div class="flex flex-row items-center gap-2">
	<i class="{icon} text-xl sm:text-xl"></i>
	<div class="text-xl sm:text-xl">{Math.floor(Math.random() * 21) + 1}</div>
</div>
