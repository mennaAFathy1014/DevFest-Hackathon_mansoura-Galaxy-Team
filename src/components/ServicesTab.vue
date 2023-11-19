<template>
  <div v-show="isActive">
    <slot></slot>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'

isActive = ref(false)
</script>
