<template>
  <div>
    我是test組件
  </div>
</template>

<script setup>
import {ref} from 'vue'
const name = ref('test name')
const setName = ()=>{
  name.value = 'test new name'
}
defineExpose({
  name,setName
})
</script>

<style scoped>
</style>