<template>
    <nav>
        <ul>
            <li v-for="item in menu" :key="item.id">
                <a :href="item.href">{{ item.titolo }}</a>

            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'AppNavBar',
    data() {
        return {
            menu: [
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 1
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 2
                },
                {
                    href: '#',
                    titolo: "Tv",
                    active: false,
                    id: 3
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 4
                },
                {
                    href: '#',
                    titolo: "Shop",
                    active: false,
                    id: 5
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 6
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 7
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 8
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 9
                },
                {
                    href: '#',
                    titolo: "Characters",
                    active: false,
                    id: 10
                },
            ]
        }
    },
    components: {

    }
}
</script>

<style scoped>
ul {
    list-style-type: none;
}
</style>