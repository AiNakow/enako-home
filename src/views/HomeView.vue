<template>
  <div class="home">
    <div class="content">
      <el-image
        class="circular-image"
        src="https://enako-bucket.s3.ap-northeast-1.amazonaws.com/public/assets/enako.jpg"
        fit="cover"
      />
      <h1 class="title">Enako 的小窝</h1>
      <p class="description">喵呜~</p>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ElImage } from 'element-plus';
</script>

<style scoped>
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  text-align: center;
  padding: 20px;
}

.circular-image {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  margin: 20px auto;
}

.title {
  font-size: 24px;
  margin: 10px 0;
}

.description {
  font-size: 16px;
  color: #666;
}
</style>