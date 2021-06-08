<template>
  <div class="blue_line">
    <div class="container">
      <div class="service">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <span>digital comics</span>
      </div>
      <div class="service">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <span>dc merchandise</span>
      </div>
      <div class="service">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <span>subscription</span>
      </div>
      <div class="service">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <span>comic shop locator</span>
      </div>
      <div class="service">
        <img id="visa" src="../assets/img/buy-dc-power-visa.svg" alt="">
        <span>dc power visa</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "BlueLine"
}
</script>

<style>
    .container {
      display: flex;
    }
    .service {
        padding: 0 20px;
    }
    .blue_line {
      height: 130px;
      line-height: 130px;
      background-color: #0082f9;
    }
    span {
      padding-left: 10px;
      color: white;
      font-size: 12px;
      text-transform: uppercase;
      cursor: pointer;
    }
    img {
      height: 40px;
      vertical-align: middle;
      cursor: pointer;
    }
    #visa {
      height: 30px;
    }
</style>