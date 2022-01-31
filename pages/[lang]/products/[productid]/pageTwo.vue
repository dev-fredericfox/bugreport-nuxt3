<script setup lang="ts">
definePageMeta({
  layout: 'english',
});
const route = useRoute();
const language = route.params.lang
const product = route.params.productid
</script>

<template>
<div>
Hi I am a {{language}} page and product id: {{product}}
<NuxtLink to="/fr/products/1234/pageThree">Take me to the french Site</NuxtLink>
</div>
</template>