<template>
   <div class="flex items-center justify-center h-screen">
      <i-frame v-model:src="url"></i-frame>
   </div>
</template>

<script setup>
import { ref } from 'vue'
import iFrame from '@/components/iFrame'

const url = ref(import.meta.env.VITE_APP_BASE_API + "/doc.html")
</script>

<style scoped>
/* 这里可以添加自定义样式 */
</style>