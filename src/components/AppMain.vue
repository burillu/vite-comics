<template>
    <main class="text-white my-primary">

        <div class="container">

            <AppList />
        </div>

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