<script>
export default {
    name: "Jumbotron",
    data() {
        return {
            img: "./public/TVD_cast.jpg"
        }
    }
}
</script>

<template>
    <img class="Jumbotron" :src="img" alt="">
</template>

<style>
.jumbotron {
    width: 100%;
    height: 200px;
}
</style>