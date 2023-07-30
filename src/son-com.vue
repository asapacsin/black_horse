<script setup>
const emit = defineEmits(['get-message'])
const sendMsg = ()=>{
  emit('get-message','this is son msg')
}
</script>

<template>
    <div>
      <div>子組件</div>
      <button @click="sendMsg">sendMsg</button>
    </div>
</template>
    
<style scoped>
</style>