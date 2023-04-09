<script>
export default {
	setup() {
		return {
			bios: [
				{
					id: 1,
					bio:
						'William Walsh, also known as Walshe, is a self-taught full-stack developer with a passion for video games. With his dedication to continuously learning and staying up-to-date with the latest technologies, he has developed a wide range of skills and expertise in web development, including front-end and back-end development, database management, and more. His strong problem-solving skills and attention to detail make him a valuable asset to any team he works with.

Walshe's love for video games and technology began at a young age and has continued to inspire him throughout his career. He is constantly seeking new and innovative ways to incorporate his passion into his work and projects. In his free time, he enjoys playing video games and tinkering with new technologies to explore their potential applications.

Overall, William Walsh, or Walshe, is a driven and talented developer with a unique perspective and a passion for innovation. His commitment to excellence and his love for video games make him an asset to any team or project he works on.',
				},
				{
					id: 2,
					bio:
						'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nihil vel illum asperiores dignissimos cumque quibusdam et fugiat voluptatem nobis suscipit explicabo, eaque consequatur nesciunt, fugit eligendi corporis laudantium adipisci soluta?',
				},
			],
		};
	},
};
</script>

<template>
	<div class="block sm:flex sm:gap-10 mt-10 sm:mt-20">
		<!-- About profile image -->
		<div class="w-full sm:w-1/4 mb-7 sm:mb-0">
			<img
				src="@/assets/images/profile.jpeg"
				class="rounded-xl w-96"
				alt=""
			/>
		</div>

		<!-- About details -->
		<div class="w-full sm:w-3/4 text-left">
			<p
				v-for="bio in bios"
				:key="bio.id"
				class="font-general-regular mb-4 text-ternary-dark dark:text-ternary-light text-lg"
			>
				{{ bio.bio }}
			</p>
		</div>
	</div>
</template>
