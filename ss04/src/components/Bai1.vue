<template>
  <div>
    <button @click="handleClick">click {{ count }} lần</button>
  </div>
</template>

<script  setup>
import { ref } from 'vue';

    let count = ref(0);
    const handleClick =()=>{
        count.value++
    }
</script>

<style>

</style>