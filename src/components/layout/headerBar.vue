<style lang="sass">
	header {
		background: #1E89E0;
		color: #fff;
		position: fixed;
		width: 100%;
		padding: 10px;
		span {
			display: block;
		}
		.title {
			font-size: 20px;
			display: inline-block;
			margin-bottom: 5px;
		}
		.sub-title {
			font-size: 14px;
		}
	}
</style>

<template>
	<header>
		<span class="title">{{ title }}</span>
		<span class="sub-title">{{ subtitle }}</span>
	</header>
</template>

<script>
	export default {
		props: ['title','subtitle'],
	}
</script>