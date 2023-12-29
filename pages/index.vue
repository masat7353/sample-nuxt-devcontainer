<template>
  <div :value="AAA" class="aaa" @click="name()">
    aaaa
  </div>
</template>

<script setup lang="ts">
const AAA = ref("aaa")
function name() {
  console.log("aaa")
}
</script>

<style>
.aaa {
  background-color: aqua;
}
</style>