<template>
	<div class="bg-gray-800 flex text-white max-h- h-screen">
		<div class="w-56 drop-shadow-md">
			<h3 class="font-semibold  p-6 pt-3 block">Skateboard</h3>
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
		<div class="flex-1 p-6">
			<header>
				<inputsearch />
				<!-- <dropDown>
					<avatar></avatar>
				</dropDown>
				<notifications/> -->
			</header>
		</div>
	</div>
</template>

<script lang="ts" setup>
import menuitem from "/src/layouts/nav/menu_item.vue";
import trendicon from "/src/components/icons/trendicon.vue";
import homeicon from "/src/components/icons/homeicon.vue";
import inputsearch from "/src/components/inputs/inputsearch.vue";
</script>
