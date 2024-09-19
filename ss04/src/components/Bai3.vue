<template>
  <div>
    <p>Acreage: {{ result }}</p>
    <button @click="handleWidth">Increase width</button>
  </div>
</template>

<script  setup>
import { computed, ref } from 'vue';

const width = ref(10);
const height =ref(20);

const result = computed(() => {
 const count = width.value*height.value;
 return count;
})
const handleWidth=()=>{
    width.value+=10;
}
</script>

<style>

</style>