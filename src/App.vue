<template>
  <div id="app">
   <el-container>
     <el-header class="el-header"> 
       <navT></navT>
     </el-header>
     <el-main>
       <div class="container">

       </div>
     </el-main>
     <el-footer>
       <p style="width:100%;height:200px;background:yellow"></p>
     </el-footer>
   </el-container>
   
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import navT from '@/components/nav'
export default Vue.extend({
  components:{
    navT
  }
})
</script>

<style lang="scss">
  body{
    padding:0;
    margin:0;
    background:#f9f7ae;
    background-image: url('../src/assets/love.gif') ;
    .el-header{
      margin: 0 auto;
      width: 75%;
      background:none;
    }
    .container{
      margin: 0 auto;
      background: red;
      width: 75%;
      height: 1000px;
      opacity: 0.3;
    }
  }
  

</style>
