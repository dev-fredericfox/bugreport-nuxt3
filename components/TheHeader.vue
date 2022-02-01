<script setup lang="ts">
const route = useRoute();
const language = route.params.lang
</script>

<template>
<div>
<div id="header">Current language based on route: {{language}} - I am the header, I am present on every page. Just my language should change. - Current language based on route: {{language}}</div>
</div>
</template>
<style>
#header {
    background-color: orangered;
    color: white;
}
</style>