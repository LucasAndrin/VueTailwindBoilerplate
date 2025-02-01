<script setup lang="ts">
import { RouterView } from 'vue-router';
</script>

<template>
	<Navbar />

	<div class="flex-grow p-10">
		<RouterView />
	</div>
</template>
