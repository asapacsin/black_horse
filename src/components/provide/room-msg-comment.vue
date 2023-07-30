<template>
  <div>
    底層組件
    <div>
      來自頂層組件中的數據為:{{roomData}}
    </div>
    <div>
      來自頂層組件的響應式數據
    </div>
  </div>
</template>

<script setup>
import {inject} from 'vue'
const roomData = inject('data-key')
</script>

<style scoped>
</style>