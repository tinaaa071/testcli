<template>
  <div class="about">
    <h1>This is an about page</h1>
    <!-- 將卡片元件呈現於畫面 -->
    <Card></Card>
  </div>
</template>

<script>
// 將外部卡片元件匯入
import Card from '@/components/Card-cop.vue'
// 將元件匯出
export default {
  // 區域註冊元件
  components: {
    Card
  }
}
</script>
