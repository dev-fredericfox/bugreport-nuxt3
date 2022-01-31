<script setup lang="ts">
definePageMeta({
  layout: 'french',
});
const route = useRoute();
const language = route.params.lang
const product = route.params.productid
</script>

<template>
<div>
Hi I am a {{language}} page and product id: {{product}}
<NuxtLink to="/en/products/1234/pageTwo">Take me to the english Site</NuxtLink>
</div>
</template>