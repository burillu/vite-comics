<template>
    <div class="container-fluid">
        <div class="row py-4">
            <div class="col d-flex justify-space-between align-items-center text-uppercase gx-3" v-for="item in dcList"
                :key="item.id">
                <img :src="item.src" :alt="item.titolo"><span>{{ item.titolo }} </span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {


        return {
            dcList: [
                {
                    src: '/images/buy-comics-digital-comics.png',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 1
                },
                {
                    src: '/images/buy-comics-merchandise.png',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 2
                },
                {
                    src: '/images/buy-comics-shop-locator.png',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 3
                },
                {
                    src: '/images/buy-dc-power-visa.svg',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 4
                },
                {
                    src: '/images/buy-comics-digital-comics.png',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 5
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
img {
    height: 50px;
}
</style>