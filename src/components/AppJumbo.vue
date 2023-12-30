<script>
export default {
    name: "AppJumbo",
}
</script>

<template>
    <div class="jumbo">

    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.jumbo{
    min-height: 400px;
    background-image: url(../assets/jumbotron.jpg);
    background-position: top;
}
</style>
