<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue'
import AppFeatures from './components/AppFeatures.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFeatures,
  }
}

</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain/>
    <AppFeatures/>
  </div>
</template>

<style lang="scss">
@use 'styles/general.scss' as *;
@use 'styles/partials/variables.scss' as *;

</style>
