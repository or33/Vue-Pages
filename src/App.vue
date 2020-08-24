<template>
  <div id="app">
    <Sidebar></Sidebar>
    <Header></Header>
    <CardsHolder></CardsHolder>
  </div>
</template>

<script>
import CardsHolder from "./components/CardsHolder.vue";
import Header from "./components/Header.vue"
import Sidebar from "./components/Sidebar"



export default {
  components: {
    CardsHolder,  Sidebar, Header
}
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');

body{
  
  background: rgb(238, 251, 252);
}

</style>
