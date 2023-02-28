<script>
//import componenti
import Jumbotron from "./jumbotron.vue";
import MainFooter from "./MainFooter.vue";

export default {
  //dichiarazione
  components: { MainFooter, Jumbotron },
};
</script>
<template>
  <div>
    <Jumbotron />
    <div class="cardContainer">
      <div>
        <button></button>
      </div>
    </div>
    <MainFooter />
  </div>
</template>
<style lang="scss" scoped>
@use "../../assets/styles/mixins.scss" as *;
@use "../../assets/styles/variables.scss" as *;
.cardContainer {
  button {
  }
}
</style>
