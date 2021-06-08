<template>
    <div class="jumbotron">
        <img src="../assets/img/jumbotron.jpg" alt="Jumbotron">
        <div class="series">
            <span>current series</span>
        </div>
    </div>
</template>

<script>
export default {
    name: "Jumbotron"
}
</script>

<style lang="scss" scoped>
    .jumbotron {
        position: relative;
        height: 300px;

        img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: top;
        }

        span {
            position: absolute;
            left: 150px;
            top: 280px;
            display: inline-block;
            padding: 10px 15px;
            text-transform: uppercase;
            background-color: #0082f9;
            color: white;
            font-weight: bolder;

            &:hover {
                    background-color: white;
                    color: #0082f9;
                }
        }

    }
</style>