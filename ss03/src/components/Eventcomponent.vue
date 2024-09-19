<template>
  <div v-on:click="handleClick">Click me </div>
  <button v-on:click="handleDelete(1)">Delete</button>
  <button v-on:click="handleGetEvent">Event info</button>
  <form @submit.prevent="hadleSubmit" action="">submit
    <button type="submit">submit</button>
  </form>
  <button @keydown.esc="handleCloseForm">Đóng form</button>
</template>

<script  setup>
const handleClick =()=>{
  console.log("Clicked");
  
}
const handleDelete =(id)=>{
  console.log("id: ",id);
  
}
const handleGetEvent =(event)=>{
  console.log("Event info", event);
  
}
const hadleSubmit =()=>{
  alert("submited");
}
const handleCloseForm =()=>{
  alert("Đóng form");
}
</script>
   
<style></style>
