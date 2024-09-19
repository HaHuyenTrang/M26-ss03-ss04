<template>
  <div>
    <input v-model="inputValue" type="number" name="" id="">
    <button @click="handleClick">Add to cart</button>
    <p>Tổng tiền trong giỏ hàng: {{ inputValue }}</p>
  </div>
</template>

<script  setup>
import { ref, watch } from 'vue';

const inputValue = ref();
watch(inputValue, (newValue, oldValue) => {
  return newValue
});
const handleClick=()=>{
    inputValue= newValue
}
</script>

<style>

</style>