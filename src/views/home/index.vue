<script setup lang="ts">
import { useRouter } from "vue-router";
const router = useRouter();
</script>

<template>
  首页
  <button @click="() => router.push({ path: '/mine', query: { id: 1 } })">
    跳转到个人中心
  </button>
</template>

<style></style>
