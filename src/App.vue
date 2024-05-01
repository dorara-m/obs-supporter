<script setup>
import EndTime from './components/EndTime.vue'
</script>

<template>
  <div>
    <h1>obs-supporter</h1>
    <EndTime class="rightTop" />
  </div>
</template>

<style scoped>
h1 {
  display: none;
}
.rightTop {
  position: absolute;
  top: 50px;
  right: 100px;
}
</style>
