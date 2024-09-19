<template>
  <div>
    <h1>Reactive</h1>
    <p>id: {{ user.id }}</p>
    <p>name: {{ user.name }}</p>
    <button @click="handleIncrease">increase id</button>
  </div>
</template>

<script  setup>
import { reactive } from 'vue';

const handleIncrease =()=>{
    user.id++;
}
const user= reactive({
    id:1,
    name:"Hà Huyền Trang"
})
</script>

<style>

</style>