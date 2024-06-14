<template>
    <div>Index Page</div>

    <!-- "to" autocomplete broken here -->
    <NuxtLink to="/user-1">User Page</NuxtLink>
</template>

<script setup lang="ts">
    definePageMeta({ name: 'index' })

    const route = useRoute() // Autocomplete broken here 
</script>
