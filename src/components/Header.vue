<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <nav>
                <ul>
                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li>
                        <a class="active" href="#">Comix</a>
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
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
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
            padding: 20px 20px;
            color: #1d1d1d;
            font-size: 14px;

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