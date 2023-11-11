<template>
    <header>
        <div class="container d-flex justify-content-between align-items-center h-100">
            <div class="my-img-container">
                <img :src="srcLogo" alt="logo-dc">
            </div>
            <AppNavBar />
        </div>

    </header>
</template>

<script>
import AppNavBar from './header/AppNavBar.vue';

export default {
    name: 'AppHeader',
    data() {
        return {
            srcLogo: '/images/dc-logo.png'
        }
    }, components: {
        AppNavBar
    }
}
</script>

<style lang="scss" scoped>
header {
    background-color: white;
    font-family: 'Open Sans Condensed';
    font-size: 16px;
    height: 80px;

    .my-img-container img {
        width: 50px;
    }
}
</style>