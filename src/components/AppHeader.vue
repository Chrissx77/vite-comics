<script>
export default {
  name: "AppHeader",

  props:{
    links: Array,
  }
}

</script>

<template>
  <header>
    <div class="logo">
      <a href="#">
        <img src="/dc-logo.png" alt="">
      </a>
    </div>

    <div class="menu">
      <ul>
        <li v-for="link in links">
          <a :href= "link.url" :class="link.current ? 'active' : '' ">
            {{ link.text }}
          </a>
        </li>
      </ul>
    </div>

  </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

header {
  @include contain;
  @include center;
  padding: 1rem;

  ul {
    list-style: none;
    @include center;

    li {
      padding: 1rem;

      a {
        text-decoration: none;
        color: #3e4446;
        font-size: 0.9rem;
        font-weight: bold;
      }
    }
  }

  .active {
    color: $primary;
  }


}
</style>
