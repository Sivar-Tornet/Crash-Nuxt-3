<script setup>
const route = useRoute()
const nuxtApp = useNuxtApp()

console.log(nuxtApp)
// When accessing /posts/1, route.params.id will be 1
console.log(route.params)
</script>

<template>
    <div>
        event id: {{ $route.params.id }}
    </div>
</template>
