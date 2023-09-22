<script setup>
import Project from './Project.vue';
import ecom_image from '../assets/ecom.jpeg';
import laundry_image from '../assets/laundry.jpeg';
import library_image from '../assets/lms_dashboard.jpeg';
import question_image from '../assets/study_questions.jpeg';
</script>

<template>
	<section class="md:scroll-mt-16 md:snap-center md:h-screen text-white bg-gray-900 py-16">
		<article>
			<h2 class="text-4xl px-4 pt-4 font-bold">Projects</h2>
			<div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-4 p-4">
				<Project>
					<template #image>
						<img :src="ecom_image" alt="" class="w-full">
					</template>
					<template #head>
						Ecommerce Website
					</template>
					<template #body>
						Simple Ecommerce Website build with Laravel, Vue.js and Tailwind CSS
						<a href="https://github.com/sibber11/ecom" class="inline-flex flex-row">
							<span class="text-blue-500">Learn More</span>
							<svg height="20" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="32" class="inline fill-blue-500">
								<path
									d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z">
								</path>
							</svg>
						</a>
					</template>
				</Project>
				<Project>
					<template #image>
						<img :src="laundry_image" alt="" class="w-full">
					</template>
					<template #head>
						Laundry Website
					</template>
					<template #body>
						Simple Laundry Website build with Laravel, Vue.js and Tailwind CSS
						<a href="https://github.com/sibber11/haundry" class="inline-flex flex-row">
							<span class="text-blue-500">Learn More</span>
							<svg height="20" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="32" class="inline fill-blue-500">
								<path
									d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z">
								</path>
							</svg>
						</a>
					</template>
				</Project>
				<Project>
					<template #image>
						<img :src="library_image" alt="" class="w-full">
					</template>
					<template #head>
						Library Management
					</template>
					<template #body>
						Simple Library Management build with Laravel, Vue.js and Tailwind CSS
						<a href="https://github.com/sibber11/library-management" class="inline-flex flex-row">
							<span class="text-blue-500">Learn More</span>
							<svg height="20" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="32" class="inline fill-blue-500">
								<path
									d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z">
								</path>
							</svg>
						</a>
					</template>
				</Project>
				<Project>
					<template #image>
						<img :src="question_image" alt="" class="w-full">
					</template>
					<template #head>
						Question Bank
					</template>
					<template #body>
						Simple Question Bank build with Laravel, Vue.js and Tailwind CSS
						<a href="https://github.com/sibber11/study" class="inline-flex flex-row">
							<span class="text-blue-500">Learn More</span>
							<svg height="20" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="32" class="inline fill-blue-500">
								<path
									d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z">
								</path>
							</svg>
						</a>
					</template>
				</Project>
			</div>
		</article>
</section></template>
