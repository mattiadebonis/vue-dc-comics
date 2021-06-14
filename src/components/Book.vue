<template>
    <div>
        <img :src="item.thumb" alt="">
        <p>{{item.series}}</p>

        <p>{{item.price}}</p>
        <p>{{item.type}}</p>

    </div>
    
</template>

<script>

    export default {
        name: "Book",
        props : ["item"]
    }

</script>

<style scoped>
p{
    color:white;
}

</style>