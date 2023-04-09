<script>
	export default {
		setup() {
			return {
				projects: [
					{
						id: 1,
						title: 'Project Title 1',
						image: '@/assets/images/project1.png',
						details:
							'William Walsh, also known as Walshe, is a self-taught full-stack developer with a passion for video games. With his dedication to continuously learning and staying up-to-date with the latest technologies, he has developed a wide range of skills and expertise in web development, including front-end and back-end development, database management, and more. His strong problem-solving skills and attention to detail make him a valuable asset to any team he works with.',
						tools: ['Vue.js', 'Tailwind CSS'],
						demoLink: 'https://example.com',
						sourceLink: 'https://github.com/example',
					},
					{
						id: 2,
						title: 'Project Title 2',
						image: '@/assets/images/project2.png',
						details:
							'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis sagittis mauris ac velit blandit, nec suscipit nibh commodo. Donec vitae neque ut mauris vehicula lacinia. Sed nec rhoncus urna, at iaculis arcu. Sed euismod mauris euismod dui mattis dapibus.',
						tools: ['React', 'CSS'],
						demoLink: 'https://example.com',
						sourceLink: 'https://github.com/example',
					},
				],
			};
		},
	};
</script>
