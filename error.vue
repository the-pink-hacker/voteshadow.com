<template>
  <div>
    <p>{{ error }}</p>
    <button @click="handleError">Go Home</button>
  </div>
</template>

<script lang="ts" setup>
defineProps({
  error: Object,
});

const handleError = () => clearError({ redirect: "/" });
</script>
