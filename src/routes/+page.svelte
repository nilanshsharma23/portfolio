<script lang="ts">
	import PostTemplate from '../components/post/PostTemplate.svelte';
</script>

<div class="flex w-full flex-col items-center gap-4 p-8">
	<PostTemplate
		date="March 25 2020"
		content="This COVID-19 thing is getting serious now, my exams got cancelled and I had to stay home for a whole day! Apparently I have to do this for 21 more days..."
		imageSrc="/posts/lockdown-announcement.png"
	/>
	<PostTemplate
		date="January 30 2020"
		content="Well, India just had it's first official COVID-19 case, but I'm sure this will be just another flu and not something that'll drastically change the course of my life."
		imageSrc="/posts/first-covid-case.png"
	/>
	<PostTemplate
		date="April 1 2013"
		content="I have moved house and start school soon! I am now based out of Noida, India."
	/>
	<PostTemplate
		date="September 9 2009"
		content="Hello, World! I am just born and I don't really remember what happened, but I assume that I was
		crying. I am now based out of Delhi, India."
	/>
</div>
