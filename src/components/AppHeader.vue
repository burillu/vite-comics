<template>
    <header>
        header con navbar
        <AppNavBar />
    </header>
</template>

<script>
import AppNavBar from './header/AppNavBar.vue';

export default {
    name: 'AppHeader',
    data() {
        return {

        }
    }, components: {
        AppNavBar
    }
}
</script>

<style lang="scss" scoped></style>