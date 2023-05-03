<template>
  <div>
    <a :href="url">
      <img :src="imgUrl" :alt="imgDefinition">
    </a>
  </div>
</template>

<script lang="ts">
export default {
  props: {
    url: String,
    imgUrl: String,
    imgDefinition: String,
  }
}
</script>
