<script setup lang="ts">
useSeoMeta({
  title: 'NuxtHub Starter',
  description: 'A Nuxt template to build your full-stack application on the edge.'
})
</script>

<template>
  <default-header />
  <NuxtPage />
</template>

<style lang="scss">
.container {
  max-width: 1500px;
  padding: 0 10px;
  box-sizing: border-box;
  margin: 0 auto;
  width: 100%;
}
</style>
