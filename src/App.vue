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
  },


  data() {
    return {

      menu: [

        {
          text: 'CHARACTERS',
          url: '#',
          current: false,
        },

        {
          text: 'COMICS',
          url: '#',
          current: true,
        },

        {
          text: 'MOVIES',
          url: '#',
          current: false,
        },

        {
          text: 'TV',
          url: '#',
          current: false,
        },

        {
          text: 'GAMES',
          url: '#',
          current: false,
        },

        {
          text: 'COLLECTIBLES',
          url: '#',
          current: false,
        },

        {
          text: 'VIDEOS',
          url: '#',
          current: false,
        },

        {
          text: 'FANS',
          url: '#',
          current: false,
        },

        {
          text: 'NEWS',
          url: '#',
          current: false,
        },

        {
          text: 'SHOP',
          url: '#',
          current: false,
        },

      ]


    }
  },
}

</script>

<template>
  <div class="container">
    <AppHeader :links = "menu" />
    <AppMain />
    <AppFeatures />
    <AppPreFoot />
    <AppFooter />
  </div>
</template>

<style lang="scss">
@use 'styles/general.scss' as *;
@use 'styles/partials/variables.scss' as *;
</style>
