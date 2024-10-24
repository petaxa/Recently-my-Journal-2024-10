<script setup lang="ts">
const props = defineProps<{
  iconSize: string
}>()
</script>
<template>
  <div class="icons">
    <img :style="{ width: props.iconSize }" src="/oxc-logo.png" alt="">
    <img :style="{ width: props.iconSize }" src="/rolldown-logo.png" alt="">
    <img :style="{ width: props.iconSize }" src="/rspack-logo.png" alt="">
    <img :style="{ width: props.iconSize }" src="/biome-logo.svg" alt="">
  </div>
</template>
<style scoped>
.icons {
  display: flex;
  margin-top: 10%;
}
</style>
