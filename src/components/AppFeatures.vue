<script>
export default {
    name: 'AppFeatures',
}
</script>

<template>
    <div class="cards">
        <ul>
            <li>
                <div class="image">
                    <img src="../assets/buy-comics-digital-comics.png" alt="" srcset="">
                </div>
                <div class="text">
                    DIGITAL COMICS
                </div>
            </li>

            <li>
                <div class="image">
                    <img src="../assets/buy-comics-merchandise.png" alt="" srcset="">
                </div>
                <div class="text">
                    DC MERCHANDISE
                </div>
            </li>

            <li>
                <div class="image">
                    <img src="../assets/buy-comics-shop-locator.png" alt="" srcset="">
                </div>
                <div class="text">
                    SUBSCRIPTION
                </div>
            </li>

            <li>
                <div class="image">
                    <img src="../assets/buy-comics-subscriptions.png" alt="" srcset="">
                </div>
                <div class="text">
                    COMIC SHOP LOCATER
                </div>
            </li>

            <li>
                <div class="image">
                    <img src="../assets/buy-dc-power-visa.svg" alt="" srcset="">
                </div>
                <div class="text">
                    DC POWER VISA
                </div>
            </li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;


div {
    background-color: $primary;
    color: white;

    ul {
        width: 75%;
        margin: 0 auto;
        @include center;
        padding: 2rem;
        list-style: none;

        li {
            display: flex;
            align-items: center;
            div{
                padding: 0 10px;
                img{
                    width: 40px;
                }
            }
        }
    }
}
</style>



