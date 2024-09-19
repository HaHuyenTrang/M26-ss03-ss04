<template>
  <div>
    <form @submit.prevent="hadleSubmit" action="">
        <input type="text" name="" id="">
        <button type="submit" >Submit</button>
    </form>
  </div>
</template>

<script  setup>
    const hadleSubmit =()=>{
        alert("Form submission prevented!")
    }
</script>

<style>

</style>