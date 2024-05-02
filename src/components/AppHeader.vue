<script>
export default {};
</script>

<template>
  <div class="header">
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="" />
    </div>
    <div class="menu-list">
      <ul>
        <li><a href="">CHARACTERS</a></li>
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
  </div>
</template>

<style lang="scss" scoped>
.header {
    display: flex;
    justify-content: space-around;

  .logo {
    display: flex;

  }

  .menu-list {
    display: flex;
    align-items: center;

    ul {
        display: flex;
        gap: 15px;
    }
  }
}
</style>
