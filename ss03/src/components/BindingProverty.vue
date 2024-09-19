<template>
    <div>
      <h1>Hello!!!</h1>
      <img v-bind:src="url" alt="" />
      <!-- <img :src="url" alt=""> -->
      <button v-bind:disabled="isDisable">click me</button>
      <input v-bind:disabled="inputDisable" type="text" />
      <div v-bind="divAttributes">container</div>
      <p v-bind="info">nội dung</p>
      <div v-bind:class="{textRed: isTextRed}">Huyèn Cheng</div>
    </div>
  </template>
  
  <script setup>
  const url =
    "https://inkythuatso.com/uploads/thumbnails/800/2023/03/1-hinh-anh-ngay-moi-binh-minh-tren-nui-inkythuatso-09-10-45-05.jpg";
  const isDisable = false;
  const inputDisable = true;
  const divAttributes ={
    id:"container-id",
    class:"container-class",
  
  }
  const info={
    id:"paragraph",
    area:"paragraph",
  }
  const isTextRed =true;
  </script>
  
  <style>
  .textRed{
    color: red;
  }
  </style>
  