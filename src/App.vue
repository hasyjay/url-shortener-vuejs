<template>
  <div>
    <appHeader></appHeader>
    <middlePage></middlePage>
    <foooter></foooter>
  </div>
</template>

<script>

import Header from './components/Header'
import Midpage from './components/Midpage.vue'
import Footer from './components/Footer.vue'
export default {
 components:{
   appHeader: Header,
   middlePage: Midpage,
   foooter: Footer
 },
}
</script>

<style>

</style>
