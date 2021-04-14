<template>
	<header>
		<h1>{{ msg }}</h1>
		<p>Hi, my name is John Gabriel.</p>
	</header>

	<main>
		<p>Main content.</p>
    </main>

	<footer>
		<p>2021</p>
	</footer>
</template>

<script setup>
import { defineProps } from 'vue'

defineProps({
	msg: String
})

</script>

<style scoped>
</style>
