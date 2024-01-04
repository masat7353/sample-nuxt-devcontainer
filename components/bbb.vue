<template>
  <div @click="test">
    bbb{{ props }}
  </div>
</template>

<script setup lang="ts">
const test = () => {
  alert("test!!")
}
const props = defineProps<{
  title: string,
  sample: number,
  value: string
}>()


</script>
