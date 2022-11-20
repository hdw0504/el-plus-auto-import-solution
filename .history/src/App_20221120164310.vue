<script setup lang="ts">
const testClick = () => {
  setTimeout(() => {
    try {
      ElNotification({
        title: '?',
        message: '欢迎登录',
        type: 'success',
        duration: 3000,
      })
    } catch (error) {

    }
  }, 500)
}
</script>

<template>
  <div>
    <el-button @click="testClick">123</el-button>
  </div>
</template>

<style scoped>

</style>
