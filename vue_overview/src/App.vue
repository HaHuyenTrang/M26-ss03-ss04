<!-- <script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script> -->
<script setup>

import Bai1 from './components/Bai1.vue';
import Bai2 from './components/Bai2.vue';
import Bai3 from './components/Bai3.vue';
import Bai4 from './components/Bai4.vue';
import Bai5 from './components/Bai5.vue';
import Bai6 from './components/Bai6.vue';
import Bai7 from './components/Bai7.vue';
import Bai8 from './components/Bai8.vue';
import FooterComponent from './components/FooterComponent.vue';
import Header from './components/Header.vue';
import Modal from './components/Modal.vue';
import User from './components/User.vue';
</script>
<template>
  <div>
    <h1>hello!!!</h1>
    <Header></Header>
    <FooterComponent></FooterComponent>
    <User></User>
    <Modal></Modal>
    <Bai1></Bai1>
    <Bai2></Bai2>
    <Bai3></Bai3>
    <Bai4></Bai4>
    <Bai5></Bai5>
    <Bai6></Bai6>
    <Bai7></Bai7>
    <Bai8></Bai8>
  </div>
</template>

<!-- <style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style> -->
