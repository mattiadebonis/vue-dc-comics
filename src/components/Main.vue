<template>
    <main>
        <Books />
    </main>
</template>

<script>
import Books from "./Books.vue"
export default {
    name:"Main",
    components: {
        Books : Books
    }
}

</script>

<style scoped>
    main{
        background-color: black;
        width: 100%
    }
</style>