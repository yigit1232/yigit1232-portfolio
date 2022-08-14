<script setup>
import { RouterLink, RouterView } from 'vue-router';
import Footer from '@/components/Footer.vue';
</script>

<template>
<div>
    <main id="main">
    <RouterView />
    </main>
    <el-backtop :bottom="100">
    <div
      style="
        height: 100%;
        width: 100%;
        background-color: var(--el-bg-color-overlay);
        box-shadow: var(--el-box-shadow-lighter);
        text-align: center;
        line-height: 40px;
        color: #1989fa;
      "
    >
      <el-icon><CaretTop /></el-icon>
    </div>
  </el-backtop>
    <Footer/>
</div>

</template>

