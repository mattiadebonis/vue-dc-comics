<template>
    <footer class="flex">
        <!-- prima colonna -->
        <div>
            <div class="menu_footer">
                <h5>DC Comics</h5>
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
                <h5>Shop</h5>
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
                <h5>DC</h5>
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
                <h5>Sites</h5>
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

    .menu_footer h5{
        text-transform: uppercase;
        color: white;
    }

    .menu li{
        color: gray;
        list-style: none;

    }
    
</style>

