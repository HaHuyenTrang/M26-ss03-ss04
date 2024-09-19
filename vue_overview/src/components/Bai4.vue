<template>
  <div>
    <h1>Danh sách kết quả</h1>
    <p>{{ a }}+ {{ b }} = {{ result }}</p>
    <p>{{ a }}- {{ b }} = {{ subtract }}</p>
    <p>{{ a }}* {{ b }} = {{ multiply }}</p>
    <p>{{ a }}/ {{ b }} = {{ divide }}</p>

  </div>
</template>

<script lang="ts" setup>
    let a =10
    let b=10
    const result = a+b
    const subtract = a-b
    const multiply = a*b
    const divide = a/b

</script>

<style>

</style>