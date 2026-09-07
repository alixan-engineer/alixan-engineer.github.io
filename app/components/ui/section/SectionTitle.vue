<script setup lang="ts">
withDefaults(defineProps<{ as?: 'h1' | 'h2' | 'h3' }>(), { as: 'h2' });
</script>

<template>
	<component :is="as"
		class="max-md:text-3xl md:text-4xl lg:text-5xl font-black text-center text-balance whitespace-pre-line"
	>
		<slot />
	</component>
</template>
