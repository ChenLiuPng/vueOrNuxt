<script setup lang="ts">
import { useRouter } from "vue-router";
const router = useRouter();
</script>

<template>
  个人中心
  <button @click="() => router.push({ path: '/home', query: { id: 2 } })">
    跳转到首页
  </button>
</template>

<style></style>
