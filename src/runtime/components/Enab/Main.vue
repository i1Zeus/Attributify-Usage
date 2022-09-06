<template>
  <!-- Application -->
  <div class="p-10 w-full h-full">
    <Card />
  </div>
</template>


<script setup>
const props = defineProps({
  app: {
    type: Object,
    required: true,
  },
});
</script>
