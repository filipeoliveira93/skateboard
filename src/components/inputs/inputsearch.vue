<template>
	<div class="relative my-1 mx-1">
		<input type="text " class="w-full px-4 bg-gray-600 placeholder-white py-2 rounded-3xl opacity-30 outline-none focus:outline-non focus:opacity-50 ease duration-200" placeholder="search" />
		<searchicon class="w-9 h-9 absolute text-gray-500 top-0.5 right-3 hover:text-gray-100 ease duration-200" />
	</div>
</template>

<script lang="ts" setup>
import searchicon from "/src/components/icons/searchicon.vue";
</script>
