<template>
    <div class="footer_bottom">
      <div class="container">
            <div class="button">
                <a href="#">sign-up now!</a>
            </div>
            <div class="social">
                <ul>
                    <li>
                        <a class="follow" href="#">FOLLOW US</a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </a>
                    </li>
                </ul>
            </div>
      </div>
    </div>
</template>

<script>
export default {
    name: "FooterBottom"
}
</script>

<style lang="scss" scoped>
    .container {
        display: flex;
        justify-content: space-between;
    }
    .footer_bottom {
        position: relative;
        z-index: 5;
        height: 100px;
        line-height: 100px;
        background-color: #303030;
    }
    .button a {
        text-decoration: none;
        text-transform: uppercase;
        padding: 10px 10px;
        border: 2px solid #0082f9;
        color: white;
        font-weight: bolder;
        font-size: 14px;

        &:hover {
            border: 2px solid white;
            color: #0082f9;
        }
    }
    .follow {
        text-decoration: none;
        color:#0082f9;
        font-size: 14px;
        font-weight: bolder;
        vertical-align: middle;

        &:hover {
            color: white;
        }
    }
    ul {
        display: flex;
        list-style: none;

        li a {
            padding: 0 8px;
        }
    }
    img {
        height: 30px;
        vertical-align: middle;
    }
</style>