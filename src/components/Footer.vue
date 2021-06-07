<template>
    <footer>
        <div class="container">
            <div class="footer_left">
                <ul>
                    <li>
                        <h4>DC COMICS</h4>
                    </li>
                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li>
                        <a href="#">Comix</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">Tv</a>
                    </li>
                    <li>
                       <a href="#">Games</a> 
                    </li>
                    <li>
                       <a href="#">Videos</a> 
                    </li>
                    <li>
                       <a href="#">News</a> 
                    </li>
                </ul>
                <ul>
                    <li>
                        <h4>DC</h4>
                    </li>
                    <li>
                        <a href="#">Terms of use</a>
                    </li>
                    <li>
                        <a href="#">Privacy Policy (New)</a>
                    </li>
                    <li>
                        <a href="#">Ad Choices</a>
                    </li>
                    <li>
                        <a href="#">Advertising</a>
                    </li>
                    <li>
                        <a href="#">Jobs</a>
                    </li>
                    <li>
                        <a href="#">Subscriptions</a>
                    </li>
                    <li>
                        <a href="#">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="#">Ratings</a>
                    </li>
                    <li>
                        <a href="#">Shop Helps</a>
                    </li>
                    <li>
                        <a href="#">Contact Us</a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h4>SITES</h4>
                    </li>
                    <li>
                        <a href="#">DC</a>
                    </li>
                    <li>
                        <a href="#">MAD Magazine</a>
                    </li>
                    <li>
                        <a href="#">DC Kids</a>
                    </li>
                    <li>
                        <a href="#">DC Universe</a>
                    </li>
                    <li>
                        <a href="#">DC Power Visa </a>
                    </li>
                </ul>
            </div>
            <div class="footer_right">
                <img src="../assets/img/dc-logo-bg.png" alt="Big-Logo DC">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss" scoped>
    footer {
        height: 330px;
        background-image: url(../assets/img/footer-bg.jpg);
        .footer_left {
            display: flex;

            ul {
                list-style: none;
                margin: 20px 20px;
                li {
                    padding: 2px 0;
                }
                li a {
                    text-decoration: none;
                    color: white;
                    font-size: 13px;
                    color: #797979;

                    &:hover {
                        color: white;
                    }
                }
            }
        }
    }
    h4 {
        color: white;
        margin-top: 20px;
        margin-bottom: 8px;
    }
    .container {
        display: flex;
        justify-content: space-between;
    }
    .footer_right img {
        position: relative;
        bottom: 45px;
        height: 400px;
    }
</style>