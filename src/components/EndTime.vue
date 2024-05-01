<script setup>
import dayjs from 'dayjs'
import { ref } from 'vue'

const count = ref(0)
// パソコンの現在時刻取得
const now = dayjs().format('YYYY-MM-DD')
// 現在時刻+1時間した
const end = dayjs().add(1, 'hour').format('HH:mm')
</script>

<template>
  <p>今日の配信は{{ end }}まで</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
