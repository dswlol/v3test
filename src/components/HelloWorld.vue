<template>
  <p>
    <div id="divdite" contenteditable="true">
        <span class="" contenteditable="false">主要(<text>aaa</text>,<text>bbb</text>)</span>
        <span contenteditable="false">主要按钮2</span>
    </div>
  wuchgao  8081
  </p>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
.divdite{
  height: 300px;
  background: bisque;
}
</style>