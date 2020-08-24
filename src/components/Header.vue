<template>
  <div class="header">
            <h4>Best Tenders</h4>
            <font-awesome-icon icon="bell" id="bell"/>
            <font-awesome-icon icon="search" id="search"/>
            <input type="text" class="search">
            
         </div>
</template>

<script>
export default {

}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
    font-family: 'Quicksand', sans-serif;
    }

.header {
    display: flex;
    margin-left: 300px;
    background: transparent;
    padding: 30px;

}

h4 {
    font-size: 20px;
    margin-left: 100px;
    color: gray;
}

input {
    height: 25px;
    width: 300px;
    margin-left: 400px;
    outline: none;
    border: 1px solid rgb(165, 162, 162);
    box-shadow: 0px 0px 0px rgb(172, 172, 172);
    -webkit-box-shadow:0px 1px 1px rgb(172, 172, 172);
    -moz-box-shadow: 0px 0px 0px rgb(172, 172, 172);
    border-radius: 15px;
    padding: 3px 30px;
    
    }




</style>