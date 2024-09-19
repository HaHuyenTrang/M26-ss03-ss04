<template>
  <div>
    <div class="Header">Header</div>
    <div class="Navigation">Navigation</div>
    <div class="ul-li">
        <div class="Menu">Menu</div>
        <div class="li">
            <ul>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                
            </ul>
            <br>
            <ul>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                
            </ul>
            <br>
            <ul>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                
            </ul>
            <br>
            <ul>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                <li class="cart">cart</li>
                
            </ul>
            
        </div>
        
        <div class="Article">Article</div>
    </div>
  </div>
</template>

<script  setup>

</script>

<style>
    .Header{
        background-color: rgb(179, 173, 173);
        width: 173vh;
        height: 60px;
        text-align: center;
    }
    .Navigation{
        background-color: grey;
        width: 173vh;
        height: 40px;
        text-align: center;
    }
    .Menu{
        background-color: rgb(45, 185, 45);
        width: 200px;
        height: 100vh;
       
    }
    .Article{
        background-color: rgb(56, 56, 205);
        width: 200px;
        height: 100vh;
    }
    .ul-li{
        display: flex;
    }
    .li{
        padding: 20px;
        background-color: antiquewhite;
    }
    ul{
        display: flex;
        gap:30px;
        background-color: antiquewhite;
    }
    .cart{
        
        background-color: white;
        width: 100px;
        height: 100px;
    }
</style>