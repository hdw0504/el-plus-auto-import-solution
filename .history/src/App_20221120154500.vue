<script setup lang="ts">
function testClick() {
  ElMessage({
    type: 'success',
    message: 'ε€εΆζε',
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
