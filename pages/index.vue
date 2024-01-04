<template>
  <input type="text" v-model="test_1">
  <div :value="AAA" class="aaa" @click="name()">
    aaaa
  </div>
  <bbb title="aaa" :sample=1 v-model:value="test_1" />
</template>

<script setup lang="ts">
const test_1 = ref("CCC")
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