<template>
  <Navbar/>
  <Home/>

</template>

<script>

import Home from './components/Home.vue';
import Navbar from './components/Navbar.vue';


export default {
  name: 'App',
  components: {
    Home,
    Navbar
  }
}
</script>
<style>
  #app {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    height: 2000px;
    background-color: black !important;
    color: white !important;
  }
</style>