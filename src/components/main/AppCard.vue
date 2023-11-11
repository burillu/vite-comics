<template>
    <div class="card" style="width: 18rem;">
        <img :src="thumb" class="card-img-top" :alt="series">
        <div class="card-body">
            <h5 class="card-title">{{ series }}</h5>
            <p class="card-text">{{ price }}</p>

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

<style lang="scss" scoped></style>