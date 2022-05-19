<template>
  <div>
    <header class="header">
      <div class="header-sinistro">
        <img src="../assets/img/dc-logo.png" alt="" />
      </div>

      <div class="header-destro">
        <ul class="menu">
          <li><a href="">CHARATERS</a></li>
          <li><a href="">COMICS</a></li>
          <li><a href="">MOVIES</a></li>
          <li><a href="">TV</a></li>
          <li><a href="">GAMES</a></li>
          <li><a href="">COLLECTIBLES</a></li>
          <li><a href="">VIDEOS</a></li>
          <li><a href="">FANS</a></li>
          <li><a href="">NEWS</a></li>
          <li><a href="">SHOP</a></li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "SiteHeader",
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/variable.scss";

.header {
  width: 80%;
  border: 1px solid red;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;

  .menu {
    display: flex;

    li {
      display: flex;
      line-height: 107px;
      border: 1px solid blue;
      padding: 0 0.5rem;
    }

    &:hover {
      //   color: $brand-primary-color;
      border-bottom: 4px solid $brand-primary-color;
    }

    .a {
      color: black;

      &:hover {
        color: $brand-primary-color;
      }
      
    }
  }
}
</style>
