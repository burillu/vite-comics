<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>
<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  data() {
    return {
      msg: 'Hello World'
    }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>
<style>
h1 {
  color: red;
}
</style>