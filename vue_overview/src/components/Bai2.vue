<template>
  <div class="box">
    <p class="red">red</p>
    <p class="blue">blue</p>
    <p class="green">green</p>
  </div>
</template>

<script lang="ts" setup>

</script>

<style>
    .box{
        display: flex;
        gap:10px;
        
    }
    .red{
        text-align: center;
        border: 1px solid red;
        width: 50px;
        height: 50px;
        background-color: red;
    }
    .blue{
        text-align: center;
        border: 1px solid blue;
        width: 50px;
        height: 50px;
        background-color: blue;
    }
    .green{
        text-align: center;
        border: 1px solid green;
        width: 50px;
        height: 50px;
        background-color: green;
    }
</style>