<script>
export default {
    name: 'AppPreFoot'
}
</script>

<template>
    <div class="back">

        <div class="container">
            <div class="box-text">
                <div class="comincsShop">
                    <div class="cominc">
                        <h3>DC COMINCS</h3>
                        <ul>
                            <li>Characters</li>
                            <li>Comincs</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Video</li>
                            <li>News</li>
                        </ul>
                    </div>

                    <div class="shop">
                        <h3>SHOP</h3>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>

                </div>

                <div class="dc">
                    <h3>DC</h3>
                        <ul>
                            <li>Term of Use</li>
                            <li>Privacy Police (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Job</li>
                            <li>Subscription</li>
                            <li>Talent Workshops</li>
                            <li>CPSR Certificates</li>
                            <li>Rating</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                </div>
                <div class="sites">
                    <h3>SITES</h3>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kinds</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                </div>
            </div>
            <div class="box-logo">
                <img src="../assets/dc-logo-bg.png" alt="" srcset="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.back {
    color: white;
    background-image: url(../assets/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

    .container {
        @include contain;
        display: flex;
    }

    ul{
        list-style: none;
        li{
            color: #b1b1b1;
            font-size: 0.8rem;
        }
    }

    
    
}

.box-text {
    width: 50%;
    display: flex;
    padding: 30px 0;
    padding-right: 15px;

    .comincsShop,.dc,.sites{
        padding: 20px 40px;
        h3{
            padding: 20px 0;
        }
        li{
            padding-bottom: 5px;
        }

    }

}

.box-logo {
    display: flex;
    justify-content: center;
    // width: 50%;
    height: 10%;
    position: relative;

    img {
        position: absolute;
        width: 500px;
        left: 0;
        top: -50px;
        z-index: 0;
    }
}
</style>