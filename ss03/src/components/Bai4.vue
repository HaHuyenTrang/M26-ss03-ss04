<template>
  <div>
    <div :class="{bg:isActive}  " :style="{backgroundColor:backgroundColor}">
      block
    </div>
  </div>
</template>

<script setup>
const isActive = true;
const backgroundColor = "#0000FF";
</script>

<style>

.bg {
 
  color: white;
}

</style>
