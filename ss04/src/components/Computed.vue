<template>
  <div>
    <h1>Computed</h1>
    <button @click="handleIncrease">Increase Index</button>
    <p>tại vị trí thứ  {{ index }} thì số Fib = {{ caculateFibonacy }}</p>
  </div>
</template>

<script  setup>
import { computed, ref } from 'vue';

const index = ref(0);


const caculateFibonacy = computed(() => {
  const fib = (n) => {
    if (n <= 1) return n;
    return fib(n - 1) + fib(n - 2);
  };

  return fib(index.value);
});
const handleIncrease = () => {
  index.value++;
};

</script>

<style>

</style>