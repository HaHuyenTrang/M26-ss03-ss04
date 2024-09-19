<template>
  <div>
    <p>company: {{ data.company }}</p>
    <p>age: {{ data.age }}</p>
    <button @click="handleClick">Change data</button>
  </div>
</template>

<script  setup>
import { reactive } from 'vue';
const handleClick=()=>{
    data.company="Rikkei Education",
    data.age=1;
}
const data= reactive({
    company: "Rikkei Academy",
    age: 2
})
</script>

<style>

</style>