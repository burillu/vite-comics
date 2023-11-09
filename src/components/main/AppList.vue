<template>
    <div class="container">
        <div class="row">
            <div class="col" v-for="item in dcList" :key="item.id">
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
                    src: '/images/buy-comics-digital-comics.png',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 2
                },
                {
                    src: '/images/buy-comics-digital-comics.png',
                    titolo: "Bbla Bla",
                    active: false,
                    id: 3
                },
                {
                    src: '/images/buy-comics-digital-comics.png',
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

<style lang="scss" scoped></style>