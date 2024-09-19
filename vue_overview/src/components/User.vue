<template>
  <div>
    <h3>User component</h3>
    <h3 class="name">{{ userName }} năm nay {{ age }} tuổi</h3>
  </div>
</template>

<script  setup>
    const userName ="Hà Huyền Trang"
    const age = 19
    console.log(userName ,"năm nay", age,"tuổi");
    
</script>

<style>
    .name{
        color: pink;
    }
</style>