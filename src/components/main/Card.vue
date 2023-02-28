<script>
export default {
  props: {
    comics: Array,
  },
};
</script>
<template>
  <div>
    <ul>
      <li
        class="card"
        v-for="comic in comics">
        <figure>
          <img
            :src="comic.thumb"
            alt="" />
        </figure>
        <figcaption>{{ comic.series }}</figcaption>
      </li>
    </ul>
  </div>
</template>
<style lang="scss" scoped>
@use "../../assets/styles/mixins.scss";
@use "../../assets/styles/variables.scss";

ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  column-gap: 10px;
  row-gap: 20px;
  margin: 40px 0;

  .card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: calc(15% - 10px);
    color: white;
    font-size: 0.7rem;
    figure {
      margin-bottom: 10px;
      img {
        width: 100px;
        height: 100px;
        object-fit: cover;
        object-position: top;
      }
    }
  }
}
</style>
