<template>
	<div class="flex items-center space-x-4">
		<div class="bg-orange-500 p-1.5 rounded-lg">
			<component :is="icon" class="w-5 v-5" />
		</div>
		<p><slot></slot></p>
	</div>
</template>

<script lang="ts" setup>
import homeicon from "/src/components/icons/homeicon.vue";
defineProps({
	icon: { default: null },
});
</script>
