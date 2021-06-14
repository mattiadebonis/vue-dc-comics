<template>
    <header class="flex">
        
        <img src="../../src/assets/dc-logo.png" alt="">
        <ul class="menu">
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
        </ul>
    </header>
    
    
</template>

<script>

export default {
    name: "Header"
}
</script>

<style scoped>
    *{
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
        header{
        width: 100%;
        justify-content: space-between;
        padding: 20px 60px;
    }

    img{
        width: 70px;
    }
    
    .flex{
        display: flex;
        align-items: center;  
    }

    .menu li{
        list-style: none;
        display: inline-block;
        text-transform: uppercase;
        font-size: 12px;
        color: black;
    }
    .menu a{
        padding-left: 15px;
        padding-right: 15px;

        text-decoration: none;
        font-weight: bold;
    }
    .menu a:hover{
        border-bottom: 2px solid blue;
    }
    .menu a:active{
        margin-bottom: 10px solid blue;
        color: blue;
    }
</style>
