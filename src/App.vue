<template>
  <div>
    <router-view/>
    <Footer v-show="$route.meta.showFooter"></Footer>
  </div>
</template>

<script>
import Footer from './components/Footer/Footer.vue'
export default {
  name: 'App',
  components: {
    Footer
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">

</style>
