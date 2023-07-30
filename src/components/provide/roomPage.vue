<template>
  <div>
    頂層組件
    <roomMsgItem />
  </div>
</template>

<script setup>
import {provide} from 'vue'
import roomMsgItem from './room-msg-item.vue'
provide('data-key','this is room data')
</script>

<style scoped>
</style>