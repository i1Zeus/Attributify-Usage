<template>
  <NuxtLayout>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup>
  import { useAppManager } from '#imports'

  const appManager = useAppManager()
  // App Configuration
  appManager.addApp({
      "name": "Enab",
      "title": "تطبيقي",
      "minWidth": 550,
      "minHeight": 600,
  })
</script>