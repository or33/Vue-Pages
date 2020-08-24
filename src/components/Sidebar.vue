<template>
<div class="wrapper">
    <div class="sidebar">
        <ul>
            <h3>Tenderfarm</h3>
            <li><a href="#" ><font-awesome-icon icon="building"/> Company</a></li>
            <li><a href="#"> <font-awesome-icon icon="search"/> Explore</a></li>
            <li><a href="#"> <font-awesome-icon icon="building"/> Latest Tenders</a></li>
            <li><a href="#"><font-awesome-icon icon="building"/> Best Tenders</a></li>
            <li><a href="#"> <font-awesome-icon icon="users"/> Team Search</a></li>
            <li><a href="#"> <font-awesome-icon icon="bell"/> Notifications</a></li>
            <li><a href="#"> <font-awesome-icon icon="envelope-open"/> Messages</a></li>
            <li><a href="#"> <font-awesome-icon icon="user"/> Profile</a></li>

    </ul>
    </div>
    
</div>
  
</template>


<script>


export default {
name: 'Sidebar',
components: {
}

}
</script>

<style scoped>
*{
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
    box-sizing: border-box;
    font-family: sans-serif;
    color: rgb(205, 238, 247);


    
}
.wrapper {
    height: 100%;
    width: 100%;
    display: block;
    position: relative;
    margin-left: -8px;
    margin-top: -9px;
}

.sidebar {
    position: fixed;
    width: 300px;
    height: 100%;
    background:linear-gradient(230deg, rgba(160,250,255,1) 5%, rgba(60,142,213,0.9745012246645414) 32%, rgba(28,81,126,1) 58%, rgba(8,48,80,1) 88%);
    padding: 30px 0;
    overflow: auto ;
}

h3 {
    font-size: 24px;
    line-height: 30px;
    margin-left: 50px;
    padding: 25px 0;
    user-select: none;
    font-weight: lighter;
    font-family: 'Quicksand', sans-serif;


}

li {
    margin-top: 20px;
    text-align: left ;
    margin-left: 50px;
    
}

a {
    font-family: 'Quicksand', sans-serif;
    font-size: 14px;
    line-height: 50px;
    cursor: pointer;
    text-transform: uppercase;

}

a:hover {
    cursor: pointer;
    font-weight: bold;
    transition: 0.8s ease, color 0.8s ease; 
    transform: translateY(-10px);
    color: rgba(7, 123, 255, 0.486);
    background: white;
    border: 1px solid transparent;
    border-radius: 30px;
    border-width: 20px;
}

</style>
