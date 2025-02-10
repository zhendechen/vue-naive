<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import { NButton } from 'naive-ui'
</script>

<template>
  <main>
    <n-checkbox v-model:checked="value">
      Checkbox
    </n-checkbox>
    <n-button>
      Default
    </n-button>
    <!-- <TheWelcome /> -->
  </main>
</template>
