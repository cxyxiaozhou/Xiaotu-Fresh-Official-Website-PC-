<template>
  <div class="App">
    <XtxShortCut></XtxShortCut>

    <XtxHeaderNav></XtxHeaderNav>
    
    <XtxBanner></XtxBanner>
    
    <XtxNewGoods></XtxNewGoods>
    
    <XtxHotBrand></XtxHotBrand>
    
    <XtxTopic></XtxTopic>
    
    <XtxFooter></XtxFooter>

  </div>
</template>

<script>

import XtxShortCut from './components/XtxShortCut'
import XtxBanner from './components/XtxBanner'
import XtxFooter from './components/XtxFooter'
import XtxHeaderNav from './components/XtxHeaderNav'
import XtxHotBrand from './components/XtxHotBrand'
import XtxNewGoods from './components/XtxNewGoods'
import XtxTopic from './components/XtxTopic'

export default {
  components: {
    XtxBanner,
    XtxShortCut,
    XtxFooter,
    XtxHeaderNav,
    XtxHotBrand,
    XtxNewGoods,
    XtxTopic,




  }


}
</script>

<style>

</style>