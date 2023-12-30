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
          <a href="#">CHARACTERS</a>
        </li>

        <li>
          <a href="#">COMICS</a>
        </li>

        <li>
          <a href="#">MOVIES</a>
        </li>

        <li>
          <a href="#">TV</a>
        </li>

        <li>
          <a href="#">GAMES</a>
        </li>

        <li>
          <a href="#">COLLECTIBLES</a>
        </li>

        <li>
          <a href="#">VIDEOS</a>
        </li>

        <li>
          <a href="#">FANS</a>
        </li>

        <li>
          <a href="#">NEWS</a>
        </li>

        <li>
          <a href="#">SHOP</a>
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
        font-size: 0.7rem;
        font-weight: bold;
      }
    }
  }


}
</style>
