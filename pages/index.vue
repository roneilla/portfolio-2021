<template>
	<main class="bg-main-light w-full p-4">
		<div class="hero flex justify-end rb-section-min-height">
			<div class="flex pb-4 md:pb-6">
				<h1 class="flex-1 leading-none self-end">
					Interaction Designer &amp; Creative Developer based in Toronto.
				</h1>
				<p class="flex-1 self-end">
					Currently creating brand experiences at ASTOUND Group.
					<br />
					Open to freelance opportunities beginning February 2022!
				</p>
			</div>
		</div>
		<div class="rb-border-top py-4 rb-section-min-height">
			<div class="flex justify-between items-center">
				<span class="flex items-center">
					<h2 class="inline text-2xl pr-4">Featured Work</h2>
					<img class="inline h-6" src="~/assets/images/down-arrow.svg" alt="" />
				</span>
				<p class="text-2xl">2020 - Current</p>
			</div>
			<div>
				<MainCaseStudy />
			</div>
		</div>
	</main>
</template>

<script>
	import MainCaseStudy from '../components/MainCaseStudy.vue'
	export default {
		components: { MainCaseStudy },
		name: 'IndexPage',
	}
</script>

<style scoped>
</style>