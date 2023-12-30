<script>
export default {
    name: "AppMainProduct",
    props: {
        details: Object,
    }
}
</script>

<template>
    <div class="card">
        <img :src=details.thumb alt="">
        <small>
            {{ details.series }}
        </small>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.card {    
    flex-basis: 15%;
    object-fit: contain;

    img {
        width: 100%;
        height: 200px;
        object-fit: cover;
        object-position:top;
    }
}
</style>
