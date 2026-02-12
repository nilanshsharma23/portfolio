<script lang="ts">
	import PostTemplate from '../components/post/PostTemplate.svelte';
</script>

<div class="flex w-full flex-col items-center gap-4 p-8">
	<PostTemplate
		date="January 3 2023"
		content="It's been a long time since I've made anything, but I decided to lock in and make an actual and finished mobile game. It's called Underwater Rush and is made with the Unity Game Engine. I love it."
		imageSrc="posts/underwater-rush.png"
		likes={8}
		comments={3}
	/>
	<PostTemplate
		date="June 30 2020"
		content="It's a whole thing now, I haven't gone outside in months, but I'm beginning to like this thing called Java. Apparently we use it to make Minecraft mods. I made this calculator with it!"
		imageSrc="/posts/calculator.png"
		likes={4}
		comments={2}
	/>
	<PostTemplate
		date="March 25 2020"
		content="This COVID-19 thing is getting serious now, my exams got cancelled and I had to stay home for a whole day! Apparently I have to do this for 20 more days..."
		imageSrc="/posts/lockdown-announcement.png"
		likes={4}
		comments={1}
	/>
	<PostTemplate
		date="January 30 2020"
		content="Well, India just had it's first official COVID-19 case, but I'm sure this will be just another flu and not something that'll drastically change the course of my life."
		imageSrc="/posts/first-covid-case.png"
		likes={20}
		comments={40}
	/>
	<PostTemplate
		date="April 1 2013"
		content="I have moved house and start school soon! I am now based out of Noida, India."
		likes={4}
	/>
	<PostTemplate
		date="September 9 2009"
		content="Hello, World! I am just born and I don't really remember what happened, but I assume that I was
		crying. I am now based out of Delhi, India."
		likes={4}
		comments={8}
	/>
</div>
