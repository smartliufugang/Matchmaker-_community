<template>
  <div>
    <el-menu  class='nav' mode="horizontal">
        <el-row  type="flex" :gutter="20">
            <el-col  :xs="24" :sm="8" :xl="8" :md="8" :lg="8">
                <el-menu-item class="nav-item">首页</el-menu-item>
            </el-col>
            <el-col  :xs="24" :sm="8" :xl="8" :md="8" :lg="8">
        <el-menu-item class="nav-item"></el-menu-item>
            </el-col>
            <el-col  :xs="24" :sm="8" :xl="8" :md="8" :lg="8">
                <el-menu-item class="nav-item"></el-menu-item>
            </el-col>
        </el-row>
        
        
    </el-menu>
  </div>
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>
 .nav{
     background:blue;
     width: 100%;
     border: 0;
     .nav-item{
         color: white;
        text-align: center;
     }
 }
</style>