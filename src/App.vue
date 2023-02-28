<script>
//import components
import AppHeader from "./components/AppHeader.vue";
import MainContent from "./components/main/MainContent.vue";
import AppFooter from "./components/AppFooter.vue";

//import dataset
import comics from "./data/comics";

export default {
  data() {},

  //dichiarazione
  components: { AppHeader, AppFooter, MainContent, comics },
};
</script>

<template>
  <div>
    <AppHeader />
    <MainContent />
    <AppFooter />
  </div>
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
  width: 1000px;
  // max-width: 1200;
  // min-width: 600px;
  margin: 0 auto;
}
img {
  max-width: 100%;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
</style>
