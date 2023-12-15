<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
  <!-- 加入環境變數 -->
  {{ name }}
  <!-- 加入按鈕 -->
  <button type="button" class="btn btn-primary">Primary</button>
</template>

<!-- 加入環境變數 -->
<script>
export default {
  data () {
    return {
      // 環境變數
      name: process.env.VUE_APP_NAME
    }
  }
}
</script>

<style lang="scss">
@import "bootstrap";
</style>
