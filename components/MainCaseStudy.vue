<template>
	<div>
		<div v-for="(caseStudy, index) in caseStudies" :key="index">
			<NuxtLink :to="`/work/${caseStudy.link}`">
				<div class="flex items-center my-4">
					<div class="flex-1 pr-6">
						<h3 class="my-4">{{ caseStudy.title }}</h3>
						<div class="my-4">
							<span
								class="tag"
								v-for="(tag, index) in caseStudy.tags"
								:key="index"
							>
								{{ tag }}
							</span>
						</div>
						<p class="my-4">{{ caseStudy.description }}</p>
					</div>
					<div class="flex-initial">
						<img :src="require('~/assets/images/' + caseStudy.imgSrc)" alt="" />
					</div>
				</div>
			</NuxtLink>
		</div>
	</div>
</template>

<script>
	import { caseStudies } from '~/data.js'

	export default {
		name: 'caseStudies',
		data() {
			return {
				caseStudies: caseStudies,
			}
		},
	}
</script>

<style scoped>
	img {
		max-width: 600px;
		width: 100%;
		object-fit: cover;
	}
</style>