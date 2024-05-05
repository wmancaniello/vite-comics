<script>
export default {
  data() {
    return {
      menu: [
        {
          title: "CHARACTERS",
          active: false,
        },
        {
          title: "COMICS",
          active: true,
        },
        {
          title: "MOVIES",
          active: false,
        },
        {
          title: "TV",
          active: false,
        },
        {
          title: "GAMES",
          active: false,
        },
        {
          title: "COLLECTIBLES",
          active: false,
        },
        {
          title: "VIDEOS",
          active: false,
        },
        {
          title: "FANS",
          active: false,
        },
        {
          title: "NEWS",
          active: false,
        },
        {
          title: "SHOP",
          active: false,
        },
      ],
    };
  },
};
</script>

<template>
  <div class="header">
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="logo" />
    </div>
    <div class="menu-list">
      <ul>
        <li v-for="item in menu" :key="item.title">
          <a href="" :class="{ active: item.active }">{{ item.title }}</a>
        </li>
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

    .active {
      font-weight: bold;
      color: blue;
    }
  }
}
</style>
