<template>
  <div class="flex justify-center items-center h-full">
    <iframe
      :src="src"
      class="w-full h-full border-none"
      @load="onLoad"
    ></iframe>
  </div>
</template>

<script setup>
import { ref, defineProps, defineEmits } from 'vue'

const props = defineProps({
  src: {
    type: String,
    required: true
  }
})

const emit = defineEmits(['load'])

const onLoad = () => {
  emit('load')
}
</script>

<style scoped>
/* 这里可以添加自定义样式 */
</style>