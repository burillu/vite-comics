<template>
    <main class="bg-primary text-white">
        questo è il main
        <AppList />
    </main>
</template>
<script>
import AppList from './main/AppList.vue';

export default {
    name: 'AppMain',
    data() {
        return {

        }
    },
    components: {
        AppList
    }
}
</script>
<style lang="scss" scoped></style>