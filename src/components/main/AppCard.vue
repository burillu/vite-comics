<template>
    <div class="my-card">
        <div class="my-img-container">
            <img :src="thumb" class="card-img-top" :alt="series">
        </div>

        <div class="my-card-body">
            <h5 class="my-card-title">{{ series }}</h5>
            <p class="my-card-text">price: {{ price }}</p>

        </div>
    </div>
</template>

<script>
export default {
    name: 'AppCard',
    data() {
        return {

        }
    },
    props: {
        thumb: String,
        price: String,
        series: String,
        type: String
    }
}
</script>

<style lang="scss" scoped>
div.my-img-container {
    width: 10em;
    height: 10em;
    overflow: hidden;

    img {
        object-fit: cover;
        object-position: center;
    }
}
</style>