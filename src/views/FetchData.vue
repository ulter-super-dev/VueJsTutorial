<script setup lang="ts">
import FetchData from '../components/FetchData.vue'
</script>

<template>
  <div class="fetch-data-example">
    <h1>This is a fetch data from server example page. Data comes from github</h1>
    <FetchData></FetchData>
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
