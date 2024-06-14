<template>
    <!-- $route is of type "any" -->
    <div>User Page, id: {{ $route.params.id }}</div>

    <!-- "to" autocomplete broken here -->
    <NuxtLink to="/">Index Page</NuxtLink>
</template>

<script setup lang="ts">
    definePageMeta({ name: 'user' })
</script>
