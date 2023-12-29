<script>
export default {
  name: "AppHeader",
  // data() {
  //   return {


  //   }
  // },
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
        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
        </li>

        <li>
          <a href="#">TEST</a>
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
      }
    }
  }


}
</style>
