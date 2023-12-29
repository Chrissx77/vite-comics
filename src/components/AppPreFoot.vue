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
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                        </ul>
                    </div>

                    <div class="shop">
                        <h3>SHOP</h3>
                        <ul>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                        </ul>
                    </div>

                </div>

                <div class="dc">
                    <h3>DC</h3>
                        <ul>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                        </ul>
                </div>
                <div class="sites">
                    <h3>SITES</h3>
                        <ul>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
                            <li>TEST</li>
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
    width: 50%;

    img {
        width: 80%;
    }
}
</style>