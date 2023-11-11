<template>
    <nav class="">

        <ul class="nav text-secondary fw-bold  text-uppercase">
            <li class="nav-item" v-for="item in menu" :key="item.id">
                <a class="nav-link " :class="{ 'my-active': item.active }" :href="item.href">{{ item.titolo }}</a>

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
                    active: true,
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

<style lang="scss" scoped>
@use '../../assets/style/style.scss';

a.nav-link {
    color: inherit;

}

.my-active {
    color: blue;
    border-bottom: 3px solid blue;
}
</style>