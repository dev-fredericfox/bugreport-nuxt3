<script setup lang="ts">
const route = useRoute();
</script>
<template>
  <div>
      <div :key="route.params.lang">
      <TheHeader/>
      <NuxtPage :key="route.path" /> 
      </div>
  </div>
</template>
