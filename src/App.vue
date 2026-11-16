<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <main class="card">
    <p class="eyebrow">VUE 3 · 架构示意</p>
    <h1>水轮机组三维检修平台</h1>
    <p class="hello">Hello World!</p>
    <p class="description">一个最小的 Vue 示例，用于展示项目入口、组件与响应式交互。</p>
    <button type="button" @click="count++">点击计数：{{ count }}</button>
    <p class="notice">
      本仓库代码仅为 Hello World 与前端架构示意，未实现视频中的三维检修功能。
      README 中的视频仅作为项目演示参考。
    </p>
    <a href="https://github.com/caliwon2077/hydro-turbine-3d-maintenance#readme">查看项目介绍与演示视频 ↗</a>
  </main>
</template>
