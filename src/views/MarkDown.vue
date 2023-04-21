<script setup lang="ts">
import MarkDown from '../components/MarkDown.vue'
</script>

<template>
  <div class="markdown-editor">
    <h1>This is a markdown-editor page</h1>
    <MarkDown></MarkDown>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
