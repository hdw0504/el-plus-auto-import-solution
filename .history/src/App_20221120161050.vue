<script setup lang="ts">
function testClick() {
  ElNotification({
    title: '?',
    message: '欢迎登录',
    type: 'success',
    duration: 3000,
  })
}
</script>

<template>
  <div>
    <el-button @click="testClick">123</el-button>
  </div>
</template>

<style scoped>

</style>
