<script>
export default {
  data() {
    return {
      headerLinks: [
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
          title: "SHOP",
          active: false,
        },
      ],
    };
  },
};
</script>
<template>
  <header class="container">
    <div class="logo">
      <img
        src="../assets/dc-logo.png"
        alt="" />
    </div>
    <div class="nav">
      <ul>
        <li v-for="link in headerLinks">{{ link.title }}</li>
      </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use "../assets/styles/variables.scss" as *;
@use "../assets/styles/mixins.scss" as *;
.container {
  @include d-flex();
  justify-content: space-between;
  align-items: center;
}
.nav {
  li {
    margin: 0 5px;
    display: inline-block;
    font-size: 0.8rem;
  }
}
.active {
  border-bottom: 2px solid #0f82f7;
}
</style>
