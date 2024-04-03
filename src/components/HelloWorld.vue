<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="bg-blue-500">
    <button type="button" @click="count++" class="text-3xl">count is {{ count }}</button>
  </div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
