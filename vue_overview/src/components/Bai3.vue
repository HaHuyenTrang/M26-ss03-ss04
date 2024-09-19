<template>
  <div class="cart">
        <p class="image">image</p>
        <p class="title">title 
            <br>
            <br>
            <button class="button">Add to cart</button>
        </p>
  </div>
</template>

<script lang="ts" setup>

</script>

<style scoped>
    .cart{
        border: 1px solid white;
        border-radius: 20px;
        height: 260px;
    }
    .image{
        text-align: center;
        background-color: grey;
       border-top-left-radius: 20px ;
       border-top-right-radius: 20px ;
       height: 50%;
       color: black;
       font-size: 20px;
       

    }
    .title{
        text-align: center;
        background-color: white;
        border-bottom-left-radius: 20px ;
        border-bottom-right-radius: 20px ;
        height: 50%;
        color: black;
       font-size: 20px;
    }
    .button{
        border: 1px solid black;
        background-color: rgb(231, 229, 229);
        padding: 10px;
        width: 150px;
    }

</style>