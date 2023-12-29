<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFeatures from './components/AppFeatures.vue';
import AppPreFoot from './components/AppPreFoot.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFeatures,
    AppPreFoot,
    AppFooter,
  }
}

</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain/>
    <AppFeatures/>
    <AppPreFoot/>
    <AppFooter/>
  </div>
</template>

<style lang="scss">
@use 'styles/general.scss' as *;
@use 'styles/partials/variables.scss' as *;

</style>
