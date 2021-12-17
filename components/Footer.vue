<template>
	<footer style="height: 3.75rem" class="bg-main-light w-full px-4">
		<div
			id="inner-div"
			class="
				rb-border-top
				bg-main-light
				flex
				items-center
				justify-between
				px-4
				py-4
				text-base
			"
		>
			<div class="flex-1">Roneilla Bumanlag</div>
			<div class="flex-initial">
				<a href="mailto:roneillabumanlag@gmail.com"
					>roneillabumanlag@gmail.com</a
				>
			</div>
			<ul class="flex items-center justify-end flex-1">
				<li><a href="https://www.linkedin.com/in/roneilla/">LinkedIn</a></li>
				<li>
					<a href="https://www.instagram.com/eillamadethis/">Instagram</a>
				</li>
				<li><a href="https://dribbble.com/roneilla">Dribbble</a></li>
			</ul>
		</div>
	</footer>
</template>

<script>
	export default {}
</script>

<style scoped>
	#inner-div {
		font-weight: 400;
	}
	li {
		@apply mx-4;
	}
</style>