<script lang="ts">
	import PostTemplate from '../components/post/PostTemplate.svelte';
</script>

<svelte:head>
	<title>Nilansh Sharma | About</title>
</svelte:head>

<div class="flex w-full flex-col items-center gap-4 p-8">
	<div class="mb-4 block text-center text-4xl lg:hidden">Not The Social Network</div>
	<PostTemplate
		date="March 26 2025"
		content="Reedel is OUT!<br>Features include -<ul class='pl-8 list-disc'><li>Posts</li><li>Direct Messaging</li><li>Study Rooms</li><li>Tik-Tok like feature for MCQs</li><li>And More!</li></ul><a href='https://play.google.com/store/apps/details?id=com.pyscrap.reedel' class='underline' target='_blank rel='noopener noreferrer' \>Check it out!</a>"
		imageSrc="/posts/reedel-store.png"
	/>
	<PostTemplate
		date="December 4 2024"
		content="Started working on my biggest project yet. It's basically a social networking app for students."
		imageSrc="/posts/reedel-first.jpg"
	/>
	<PostTemplate
		date="August 24 2024"
		content="I made ANOTHER game in 48 hours, this time for the GMTK Game Jam! In this one you build a city, but vertically. <a href='https://play.google.com/store/apps/details?id=com.pyscrap.quizquest' class='underline' target='_blank rel='noopener noreferrer' \>Check it out!</a> "
		imageSrc="/posts/skyward-madness.png"
	/>
	<PostTemplate
		date="August 20 2024"
		content="Recently got into app development with Flutter and made an app that makes a multiple choice quiz using Artificial Intelligence. <a href='https://play.google.com/store/apps/details?id=com.pyscrap.quizquest' class='underline' target='_blank rel='noopener noreferrer' \>Check it out!</a> "
		imageSrc="/posts/quizquest.png"
	/>
	<PostTemplate
		date="June 11 2024"
		content="I made a game in 48 hours for the Mini Game Jam 160! <a href='https://pyscrap.itch.io/guiding-light' class='underline' target='_blank rel='noopener noreferrer' \>Check it out!</a> "
		imageSrc="/posts/guiding-light.png"
	/>
	<PostTemplate
		date="March 7 2023"
		content="I made a YouTube channel and started work on a new game! Check it out."
		youtubeVideoURL="https://www.youtube.com/embed/xztjDuBCvT0"
		youtubeVideoTitle="Development Log #1"
	/>
	<PostTemplate
		date="January 3 2023"
		content="It's been a long time since I've made a good project, but I decided to lock in and make an actual and finished mobile game. It's called Underwater Rush and is made with the Unity Game Engine. I love it."
		imageSrc="posts/underwater-rush.png"
	/>
	<PostTemplate
		date="November 6 2022"
		content="I made pong with the Indian Flag using Python!"
		imageSrc="posts/bharat-pong.jpg"
	/>
	<PostTemplate
		date="June 30 2020"
		content="It's a whole thing now, I haven't gone outside in months, but I'm beginning to like this thing called Java. Apparently we use it to make Minecraft mods. I made this calculator with it!"
		imageSrc="/posts/calculator.png"
	/>
	<PostTemplate
		date="March 25 2020"
		content="This COVID-19 thing is getting serious now, my exams got cancelled and I had to stay home for a whole day! Apparently I have to do this for 20 more days..."
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
		date="September 23 2009"
		content="Hello, World! I am just born and I don't really remember what happened, but I assume that I was
		crying. I am now based out of Delhi, India."
	/>
	<div class="block h-32 w-screen lg:hidden"></div>
</div>
