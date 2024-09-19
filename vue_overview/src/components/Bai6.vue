<template>
  <div>
    <h1>Họ và tên: {{ formatName(user) }}</h1>
  </div>
</template>

<script  setup>
   
        const user={
            firstName:"Hà Huyền",
            lastName:"Trang"
        }
    
   function formatName(user){
    return `${user.firstName} ${user.lastName}`;
}
</script>

<style>

</style>