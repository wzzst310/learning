<template>
  <span v-bind:title="message">
    鼠标悬停几秒钟查看此处动态绑定的提示信息！
  </span>
</template>
<script>
export default {
  name: 'App2',
  data: {
    message: '页面加载于 ' + new Date().toLocaleString()
  }
}
</script>

<style scoped>

</style>
