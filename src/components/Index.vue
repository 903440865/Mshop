<template>
  <div>
    <index-header></index-header>
    <index-navigation></index-navigation>
  </div>
</template>

<script>
import indexHeader from "./indexPage/indexHeader"
import indexNavigation from "./indexPage/indexNavigation"
export default {
  name: 'Index',
  components:{
    indexHeader,
    indexNavigation
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
