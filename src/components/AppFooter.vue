<script>
export default {
    name: 'AppFooter',
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="button">
                <a href="#">SIGN-UP NOW!</a>
            </div>
            <div class="box-socials">
                <ul class="socials">
                    <li>FOLLOW US</li>
                    <a href="#"><li><i class="fa-brands fa-facebook"></i></li></a>
                    <a href="#"><li><i class="fa-brands fa-youtube"></i></li></a>
                    <a href="#"><li><i class="fa-brands fa-x-twitter"></i></li></a>
                    <a href="#"><li><i class="fa-brands fa-pinterest"></i></li></a>
                    <a href="#"><li><i class="fa-solid fa-location-dot"></i></li></a>
                </ul>
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

footer {
    position: relative;
    z-index: 1;
    padding: 50px;
    background-color: #303030;
    
    .container {
        @include contain;
        @include center;
        .socials {
            display: flex;
            list-style: none;

            li{
                padding: 0 10px;
            }
        }

        a{
            text-decoration: none;
            color: white;
        }

        .button{
            border: 2px solid #0678e2;
            padding: 15px;

        }

        .socials{
            color: #0678e2;
            font-weight: bold;
            font-size: 1.2rem;

            a{
                li{
                    i{
                        color: #b1b1b1;
                    }
                }
            }

        }
    }
}
</style>