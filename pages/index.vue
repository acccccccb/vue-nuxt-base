<template>
  <div>
    <nuxt-link to="/list">
      <Logo></Logo>
      <el-button icon="el-icon-delete" type="primary">列表页</el-button>
    </nuxt-link>
  </div>
</template>

<script>
  import Logo from '~/components/Logo'
  export default {
      Logo
  }
</script>
<style scoped>
  body {
    background:#f5f5f5;
  }
</style>