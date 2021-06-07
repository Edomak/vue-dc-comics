<template>
    <main>
        <div class="container">
            <div class="content">
            <h1>Content goes here</h1>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: "Main"
}
</script>

<style lang="scss" scoped>
    main {
        background-color: #1d1d1d;
        color: white;
        .content {
            height: 100px;
            line-height: 100px;
            h1 {
                font-size: 20px;
            }
        }
    }
</style>