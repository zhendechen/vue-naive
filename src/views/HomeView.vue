<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import { NButton } from 'naive-ui'

document.querySelector("#abc").innerText('abc')
</script>

<template>
  <main>
    <div v-for="i in items" :key="i">{{ i }}</div>
    <n-checkbox v-model:checked="value">
      Checkbox
    </n-checkbox>
    <n-button>
      Default
    </n-button>
    <!-- <TheWelcome /> -->
  </main>
</template>
