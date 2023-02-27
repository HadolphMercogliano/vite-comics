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
      ActivePage: 0,
    };
  },
  methods: {
    switchToPage(index) {
      alert("hai cliccato il link n: " + index);
      this.ActivePage = index;
    },
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
        <li
          :class="link.active ? 'active' : ''"
          v-for="(link, index) in headerLinks"
          @click="switchToPage(index)">
          <a href="#">{{ link.title }}</a>
        </li>
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
.logo {
  height: 100px;
  img {
    padding: 10px 0;
    height: 100px;
  }
}
.nav {
  li {
    line-height: 100px;
    margin: 0 5px;
    display: inline-block;
    font-size: 0.8rem;

    a {
      color: black;
      text-decoration: none;
    }
  }
}
.active {
  border-bottom: 4px solid $blue;
}
</style>
