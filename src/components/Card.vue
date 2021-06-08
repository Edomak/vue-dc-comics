<template>
  <div class="card">
      <img :src="item.thumb" :alt="item.series">
      <h4>{{ item.series }}</h4>
  </div>
</template>

<script>
export default {
    name: "Card",
    props: ["item"]
}
</script>

<style lang="scss" scoped>
    .card {
        width: calc(100% / 6 - 20px);
        height: 150px;
        border: 1px solid black;
        margin: 30px 10px;

        img {
            width: 100%;
            height: 100%;
        }

        h4 {
            font-size: 12px;
            margin-top: 10px;
            font-weight: 400;
            cursor: pointer;

            &:hover {
                color: #0082f9;
            }
        }
    }
</style>