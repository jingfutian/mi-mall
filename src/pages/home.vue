<template>
  <div>
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
  import NavHeader from 'components/common/NavHeader'
  import NavFooter from 'components/common/NavFooter'

  export default {
    name: 'home',
    components: {
      NavHeader,
      NavFooter
    },
    data () {
      return {
        
      }
    }
  }
</script>

<style  scoped>

</style>
