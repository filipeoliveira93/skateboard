<template>
	<div>
		<h1 class="bg-blue-500">App skateboard</h1>
		<p>{{ name }}</p>
		<mycomponent />
	</div>
</template>

<script lang="ts" setup>
import mycomponent from "./components/mycomponent.vue";
const name = "Filipe";
</script>
