<template>
  <div>
    <input v-model="inputValue" type="text" name="" id="" />
  </div>
</template>

<script setup>
import { ref, watch } from "vue";

const inputValue = ref("");
watch(inputValue, (newValue, oldValue) => {
  console.log(`Giá trị đã thay đổi từ ${oldValue} đến ${newValue}`);
});
</script>

<style></style>
