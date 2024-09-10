<template>
  <div>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'drink wall',
  meta: [
    { name: 'drink wall', content: 'drink wall' }
  ],
  bodyAttrs: {
    class: 'test'
  }
})
</script>