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
                    <li>TEST</li>
                    <li>TEST</li>
                    <li>TEST</li>
                    <li>TEST</li>
                    <li>TEST</li>
                    <li>TEST</li>
                </ul>
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

footer {
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
    }
}
</style>