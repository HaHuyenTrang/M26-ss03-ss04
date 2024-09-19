<template>
  <div>
    <img :class="{bg:bgsize}" :src="url" alt="">
  </div>
</template>

<script  setup>
    const bgsize=true;
 const url="https://scontent.fhan18-1.fna.fbcdn.net/v/t39.30808-6/441310121_947566470192143_7306383490417184982_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=pqD2mdwXacIQ7kNvgGiUUVJ&_nc_ht=scontent.fhan18-1.fna&_nc_gid=AwFb-U1WEl_uY5yF1nYsa2C&oh=00_AYB2PXRdEGAUFPNi01pR3QmYB5xnnoaatSJE5KAym5uciw&oe=66F1C331"
</script>
   
<style>
    .bg{
        width: 300px;
        height: 300px;
    }

</style>