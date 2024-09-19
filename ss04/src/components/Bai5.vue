<template>
  <div>
    <h1>Giỏ hàng</h1>
    <div>
        <p>mèn mén loại 1 - số lượng {{ count }} <button @click="handleClick">tăng số lượng</button></p>
        <p>mèn mén loại 1 - số lượng {{ count2 }} <button @click="handleClick2">tăng số lượng</button></p>
        <p>mèn mén loại 1 - số lượng {{ count3 }} <button @click="handleClick3">tăng số lượng</button></p>
    </div>
    <h3>Tổng số lượng sản phẩm: {{ result }}</h3>
  </div>
</template>

<script  setup>
import { computed, ref } from 'vue';

let count = ref(0)
let count2 = ref(0)
let count3 = ref(0)
const handleClick =()=>{
     count.value++;
}
const handleClick2 =()=>{
    count2.value++;   
}
const handleClick3 =()=>{
    count3.value++;
}
const result = computed(() => {
 const counts = count.value+count2.value+count3.value;
 return counts;
})
</script>

<style>

</style>