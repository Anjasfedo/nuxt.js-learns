<script lang="ts" setup>
const route = useRoute()

console.log(route.params.id);

const nuxt = useNuxtApp()

// console.log(nuxt);
</script>

<template>
  <div>
    Page: {{ $route.params.id }}
  </div>
</template>

<style scoped></style>
