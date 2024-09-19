<template>
  <div>
    <a href="https://www.google.com" @click="handleLinkClick"
      >Truy cập Google</a
    >
    <br />
    <a href="http://www.google.com" @click="handleLinkClick"
      >Truy cập Google (http)</a
    >
  </div>
</template>

<script setup>
    const handleLinkClick =(event)=>{
        const url = event.currentTarget.href;

        // Kiểm tra định dạng đường dẫn
        if (!url.startsWith('https://')) {
        event.preventDefault(); // Ngăn chặn chuyển trang
        alert('Đường dẫn không hợp lệ. Vui lòng sử dụng đường dẫn bắt đầu bằng "https://".');
        }
        }
    
</script>

<style></style>
