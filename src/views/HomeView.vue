<script >
import {RouterLink, RouterView} from 'vue-router';
import Header from "../components/Header.vue"
export default {
  data(){
    return
  },
  components:{
    RouterLink,
    RouterView,
    Header
    
  }
}
</script>

<template>
<div class="headerShow">
  <h1>Home View</h1>
  <Header />
  <div class="showContent">
  <RouterView />
  </div>
</div>
</template>

<style lang="scss" scoped>
.headerShow{
width:100vw;
height:100vh;
}
</style>