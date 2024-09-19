<template>
  <div>
      <h1>Bai 7</h1>
      <div class="e">navbar</div>
      <div class="h">
        <div class="f">menu</div>
        <div>
          <div class="g">....</div>
          <div class="w">footer</div>
        </div>
      </div>
    </div>
</template>

<script lang="ts" setup>

</script>

<style>
    .e{
  justify-content: center;
  text-align: center;
  background-color: gray;
  width:1000px;
  height: 40px;
}
.f{
  justify-content: center;
  text-align: center;
  background-color: rgb(76, 180, 240);
  width:300px;
  height: 500px;
}
.g{
  justify-content: center;
  text-align: center;
  background-color: white;
  width:700px;
  height: 460px;

}
.h{
  display: flex;
  flex-direction: row;

}
.w{
  justify-content: center;
  text-align: center;
  background-color: rgb(195, 194, 194);
  width:700px;
  height: 40px;
}
</style>