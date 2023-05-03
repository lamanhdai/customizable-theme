<script lang="ts">
import TopHeader from './components/TopHeader/index.vue'
export default {
  components: {
    TopHeader
  }
}
</script>

<template>
  <header>
    <TopHeader :style="{width: '300px'}"/>
  </header>
</template>

<style scoped>
</style>
