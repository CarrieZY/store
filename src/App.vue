<template>
  <div id="app">
    <my-header></my-header>
    <router-view/>
    <my-footer></my-footer>
  </div>
</template>

<script>
import MyFooter from 'components/footer'
import MyHeader from 'components/header'
export default {
  name: 'App',
  components:{
    MyFooter,
    MyHeader
  }
}
</script>

<style>

</style>
