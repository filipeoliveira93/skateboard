<template>
	<div class="bg-gray-800 flex text-white max-h- h-screen">
		<div class="w-56 drop-shadow-md">
			<h3 class="font-semibold p-6 pt-3 block">Skateboard</h3>
			<nav class="p-3">
				<h1 class="opacity-50 uppercase font-semibold tracking-wider mb-6 text-xs">
					Menu
				</h1>
				<div>
					<div class="space-y-6">
						<menuitem :icon="homeicon">Discover</menuitem>
						<menuitem :icon="trendicon">Trending</menuitem>
					</div>
				</div>
			</nav>
		</div>
		<div class="p-5 flex-1">
			<header class="flex items-center justify-between border-solid">
				<inputsearch class="w-96" />
				<div class="space-x-3 flex items-center">
					<avatar class=" rounded-full w-10 h-10" />
					<span>Thomnas</span>
					<downicon class="w-4 h-4" />
					<bellicon class="w-4 h-4" />
				</div>
				<!-- <notifications /> -->
			</header>
			<h1 class="font-bold text-4xl mt-6 mb-4">Discover</h1>
			<div class="grid grid-cols-12">
				<div class="flex rounded-xl col-span-8 h-96 border border-green-500 overflow-hidden">
					<img src="https://via.placeholder.com/800x400" alt="" class="w-full object-cover" />
					<h3>How to do Basic Jumping and how to landing safely</h3>
				</div>
			</div>
		</div>
	</div>
</template>

<script lang="ts" setup>
import menuitem from "/src/layouts/nav/menu_item.vue";
import trendicon from "/src/components/icons/trendicon.vue";
import homeicon from "/src/components/icons/homeicon.vue";
import inputsearch from "/src/components/inputs/inputsearch.vue";
import avatar from "/src/components/avatar.vue";
import downicon from "/src/components/icons/down.vue";
import bellicon from "/src/components/icons/bellicon.vue";
</script>
