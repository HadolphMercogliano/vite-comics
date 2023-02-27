<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
import MainFooter from "./components/MainFooter.vue";

export default {
  components: { AppHeader, AppFooter, MainFooter },
};
</script>

<template>
  <AppHeader />
  <MainFooter />
  <AppFooter />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;900&display=swap");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "Montserrat", sans-serif;
  font-weight: 700;
}

.container {
  width: 80%;
  max-width: 1200;
  min-width: 600px;
  margin: 0 auto;
}
img {
  max-width: 100%;
}
ul {
  list-style-type: none;
}
</style>
