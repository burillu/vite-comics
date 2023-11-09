<template>
  <AppHeader />
</template>
<script>
import AppHeader from './components/AppHeader.vue';
export default {
  data() {
    return {
      msg: 'Hello World'
    }
  },
  components: {
    AppHeader
  }
}
</script>
<style>
h1 {
  color: red;
}
</style>