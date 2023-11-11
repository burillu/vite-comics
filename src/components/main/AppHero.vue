<template>
    <div>
        <img src="/images/jumbotron.jpg" alt="">
    </div>
</template>

<script>
export default {
    name: 'AppHero'
}
</script>

<style lang="scss" scoped>
@use '../../assets/style/style.scss';

div {
    height: 40vh;
    overflow: hidden;

    img {
        object-fit: cover;
        width: 100%
    }

    ;
}
</style>