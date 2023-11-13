<template>
    <ul>
        <li class="text-white text-uppercase ">{{ title }} </li>
        <li v-for="item in aList" :key="item.id">
            <a :href="item.src"> {{ item.text }} </a>
        </li>
    </ul>
</template>

<script>
export default {
    name: 'AppListFooter',
    data() {
        return {
            title: 'Blablabla Titolo',
            aList: [
                {
                    src: '#',
                    text: 'blablabla',
                    id: 1

                },
                {
                    src: '#',
                    text: 'blablab1la',
                    id: 2

                },
                {
                    src: '#',
                    text: 'blablabl2a',
                    id: 3

                },
                {
                    src: '#',
                    text: 'blablabla3',
                    id: 4

                },
                {
                    src: '#',
                    text: 'blablabla4',
                    id: 5

                },
            ]
        }
    }
}

</script>

<style lang="scss" scoped>
a {
    color: gray;
    text-decoration: none;

}
</style>