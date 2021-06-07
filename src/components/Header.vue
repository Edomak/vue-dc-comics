<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <nav>
                <ul>
                    <li v-for="(link, index) in links" :key="index">
                        <a :class="{ active: link.current }" :href="link.url"> {{ link.text }} </a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header",
    data: function () {
        return {
            links: [
                {
                    text: "Characters",
                    url: "#characters",
                    current: false
                },
                {
                    text: "Comix",
                    url: "#comix",
                    current: true
                },
                {
                    text: "Movies",
                    url: "#movies",
                    current: false
                },
                {
                    text: "Tv",
                    url: "#tv",
                    current: false
                },
                {
                    text: "Collectibles",
                    url: "#collectibles",
                    current: false
                },
                {
                    text: "Fans",
                    url: "#fans",
                    current: false
                },
                {
                    text: "News",
                    url: "#news",
                    current: false
                },
                {
                    text: "Shop",
                    url: "#shop",
                    current: false
                },
                {
                    text: "Games",
                    url: "#games",
                    current: false
                },
                {
                    text: "Games",
                    url: "#games",
                    current: false
                },

            ] 
        }
    }
}
</script>

<style lang="scss" scoped>
    header {
        height: 100px;
        line-height: 100px;

        .container {
            display: flex;
            justify-content: space-between;
        }
    }
    ul {
        list-style: none;
        display: flex;
        vertical-align: middle;

        li a {
            text-decoration: none;
            text-transform: uppercase;
            padding: 20px 10px;
            color: #303030;
            font-size: 12px;
            font-weight: bolder;

            &.active,
            &:hover {
                border-bottom: 4px solid #0082f9;
            }
        }
    }

    img {
        height: 70px;
        vertical-align: middle;
    }

</style>