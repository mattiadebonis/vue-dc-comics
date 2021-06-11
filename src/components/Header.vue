<template>
    <header class="flex">
        <img src="../../src/assets/dc-logo.png" alt="">
        <ul class="menu">
            <li><a>Characters</a></li>
            <li><a>Comics</a></li>
            <li><a>Movies</a></li>
            <li><a>TV</a></li>
            <li><a>Games</a></li>
            <li><a>Collectibles</a></li>
            <li><a>Videos</a></li>
            <li><a>Fans</a></li>
            <li><a>News</a></li>
            <li><a>Shop</a></li>
        </ul>
    </header>
    
    
</template>

<script>

export default {
    name: "Header"
}
</script>

<style scoped>
    header{
        width: 100%;
          margin: 60px 10%;

    }
    .flex{
        display: flex;
        align-items: center;
    }
    .menu li{
        list-style: none;
        display: inline-block;
        margin: 10px;
        text-transform: uppercase;
    }
</style>
