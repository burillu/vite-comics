<template>
    <footer>
        <div class="container">
            <div class="row justify-space-between">
                <div class="col-4 d-flex flex-column flex-wrap">

                    <AppListFooter />
                    <AppListFooter />
                    <AppListFooter />
                    <AppListFooter />
                    <AppListFooter />



                </div>
                <div class="col-6">
                    <img src="images/dc-logo-bg.png" alt="">
                </div>
            </div>

        </div>
        <div class="my-bg-secondary">
            <div class="container d-flex flex-row justify-content-between align-content-center">

                <button class="btn my-border text-white fw-bold text-uppercase">
                    Sign-up Now!
                </button>
                <div class="d-flex align-items-center">
                    <span class="my-text-primary text-uppercase fw-bold">
                        Follow us
                    </span>
                    <nav class="">

                        <ul class="nav text-secondary fw-bold  text-uppercase">
                            <li class="nav-item">
                                <a class="nav-link " href="#"><img src="/images/footer-facebook.png" alt="facebook"></a>

                            </li>
                            <li class="nav-item">
                                <a class="nav-link " href="#"><img src="/images/footer-twitter.png" alt="twitter"></a>

                            </li>
                            <li class="nav-item">
                                <a class="nav-link " href="#"><img src="/images/footer-youtube.png" alt="youtube"></a>

                            </li>
                            <li class="nav-item">
                                <a class="nav-link " href="#"><img src="/images/footer-pinterest.png" alt="pinterest"></a>

                            </li>
                            <li class="nav-item">
                                <a class="nav-link " href="#"><img src="/images/footer-periscope.png" alt="periscope"></a>

                            </li>
                        </ul>
                    </nav>
                </div>

            </div>


        </div>
    </footer>
</template>

<script>
import AppListFooter from './footer/AppListFooter.vue';

export default {
    name: 'AppFooter',
    data() {
        return {

        }
    },
    components: {
        AppListFooter
    }
}
</script>

<style lang="scss" scoped>
footer {
    color: white;
    background-image: url('/images/footer-bg.jpg');

}

.col-6 {


    img {
        width: 120%;

    }
}

div.flex-wrap {
    height: 500px;

    font-family: 'open sans condensed';
}

.bg-dc {
    background-image: url('/images/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-size: 50vw;
    background-position-y: -100px;
    background-position-x: -100px;
}

.my-border {
    border: 1px solid blue;
}

div.my-bg-secondary {
    height: 70px;
}
</style>