<template>
  <div id="app">
   <el-container >
     <el-header class="el-header"> 
       <navT></navT>
     </el-header>
     <el-main class="el-main">
       <div class="container">

       </div>
     </el-main>
     <el-footer style="height:200px;width:100%;background:red;"> 
       
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
    background-image: url('../src/assets/bg-top.png') ;
    background-repeat: no-repeat;
    .el-header{
      margin: 0 auto;
      width: 100%;
      background:none;
    }
    .el-main{
      margin-top: 100px;
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
