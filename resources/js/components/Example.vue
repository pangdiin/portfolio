<template>
	<div>
		<h1>HI!</h1>
		<p>{{ job }}</p>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				job : 'I am a web developer'
			}
		},
		mounted() {
			console.log('this is mounted!!')
		}
	}
</script>