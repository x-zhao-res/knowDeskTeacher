<template>
  <div class="about">
    <h2>{{ welcome }}</h2>
  </div>
</template>
<script setup>
import { ref } from 'vue'
const welcome = ref('欢迎')
</script>
<style scoped lang="scss">
.acsd{
  @include center(20px)
}
</style>
