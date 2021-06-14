<template>
    <footer class="flex">
        <!-- prima colonna -->
        <div>
            <div class="menu_footer">
                <h3>DC Comics</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>  
            <div class="menu_footer">
                <h3>Shop</h3>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>  
        </div>
        <!-- /prima colonna -->
        
        <!-- seconda colonna -->
        <div>
            <div class="menu_footer">
                <h3>DC</h3>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>   
        </div>
        <!-- /seconda colonna -->

        <!-- terza colonna -->
        <div>
            <div class="menu_footer">
                <h3>Sites</h3>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>   
        </div>
        <!-- /terza colonna -->

    </footer>
</template>

<script>

export default {
    name:"Foot"    
}

</script>

<style scoped>
    .flex{
        display: flex
    }

    footer{
        background-image: url("../assets/footer-bg.jpg");
        padding: 20px;
        text-align: left;

    }

    .menu_footer h3{
        text-transform: uppercase;
        color: white;
        margin: 10px;
        
    }
    .menu_footer ul{
        margin: 20px;
        text-align: left;

    }

    .menu_footer li{
        color: gray;
        list-style: none;
    }
    
</style>

