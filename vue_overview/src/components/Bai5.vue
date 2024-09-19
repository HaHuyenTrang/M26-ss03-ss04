<template>
  <div>
    <h1>Thông tin cá nhân</h1>
    <p>Họ và tên: {{ user.name }} </p>
    <p>Giới tính: {{ user.sex }} </p>
    <p>Ngày sinh: {{ user.date }} </p>
    <p>Email: {{ user.email }}</p>
    <p>Địa chỉ: {{ user.address }}</p>
   
  </div>
</template>

<script  setup>
    let user=
        {
            name:"HÀ HUYỀN TRANG",
            sex:"nữ",
            date:"15/06/2005",
            email:"huyetrang15625@gmai.com",
            address:"Sơn La"
        }
    
</script>

<style>

</style>