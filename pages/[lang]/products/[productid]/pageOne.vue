<script setup lang="ts">
const route = useRoute();
const language = route.params.lang
const product = route.params.productid
</script>

<template>
<div>
<p>Hi I am a page in the {{language}} language and have a product id of: {{product}}</p>
<p><NuxtLink to="/fr/products/1234/pageOne">Take me to the french Site</NuxtLink></p>
<p><NuxtLink to="/en/products/1234/pageOne">Take me to the english Site</NuxtLink></p>

<p><NuxtLink to="/en/products/7890/pageOne">Take me to the Product 7890</NuxtLink></p>
<p><NuxtLink to="/en/products/1234/pageOne">Take me to the Product 1234</NuxtLink></p>
</div>
</template>