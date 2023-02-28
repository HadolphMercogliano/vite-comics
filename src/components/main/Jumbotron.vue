<script>
export default {};
</script>
<template>
  <div class="jumbotron">
    <img
      src="../../assets/jumbotron.jpg"
      alt="" />
  </div>
</template>
<style lang="scss" scoped>
@use "../../assets/styles/mixins.scss";
@use "../../assets/styles/variables.scss";

.jumbotron {
  height: 300px;

  img {
    height: 300px;
    width: 100%;
    object-fit: cover;
    object-position: top;
  }
}
</style>
