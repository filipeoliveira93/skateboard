<template>
	<div class="bg-gray-800 flex text-white max-h- h-screen">
		<div class="border w-56">
			<h3 class="font-semibold p-6 pt-3 block">Skateboard</h3>
			<nav class="p-3">
				<h1 class="opacity-50 uppercase font-semibold tracking-wider mb-6 text-xs">
					Menu
				</h1>
				<div>
					<div class="space-y-6">
						<menuitem/>
					</div>
				</div>
			</nav>
		</div>
		<div class="border-2 flex-1 border-red-500">
			<p>Content</p>
		</div>
	</div>
</template>

<script lang="ts" setup>
	import menuitem from "/src/layouts/nav/menu_item.vue";
</script>
