<script>
//import componenti
import Jumbotron from "./jumbotron.vue";
import MainFooter from "./MainFooter.vue";
import Card from "./Card.vue";

export default {
  props: {
    comics: Array,
  },

  //dichiarazione
  components: { MainFooter, Jumbotron, Card },
};
</script>

<template>
  <div>
    <Jumbotron />
    <div class="cardContainer">
      <div class="container">
        <div>
          <button class="series">CURRENT SERIES</button>
        </div>

        <Card :comics="comics" />

        <div class="load">
          <button>LOAD MORE</button>
        </div>
      </div>
    </div>
    <MainFooter />
  </div>
</template>

<style lang="scss" scoped>
@use "../../assets/styles/mixins.scss" as *;
@use "../../assets/styles/variables.scss" as *;
.cardContainer {
  position: relative;
  background-color: #1b1b1b;
  .container {
    padding-bottom: 20px;
  }
  button {
    background-color: $blue;
    border: 1px solid $blue;
    color: white;
    font-weight: 900;
    height: 40px;
    padding: 5px 20px;
    &.series {
      position: relative;
      top: -20px;
    }
  }
  .load {
    display: flex;
    justify-content: center;
  }
}
</style>
