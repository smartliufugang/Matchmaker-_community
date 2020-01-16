<template>
  <div>
    <el-menu  class='nav' mode="horizontal">
        <el-row  :gutter="20">
            <el-col  :xs="12" :sm="12" :xl="12" :md="12" :lg="12">
                <el-menu-item class="nav-item">首页</el-menu-item>
            </el-col>
            <el-col  :xs="12" :sm="12" :xl="12" :md="12" :lg="12">
                <el-row :gutter="20">
                    <el-col :xs='12' :sm="12" :xl="12" :md="12" :lg="12">
                        <el-menu-item class="nav-item">注册</el-menu-item>
                    </el-col>
                    <el-col :xs="12" :xl="12" :sm="12" :md="12" :lg="12">
                        <el-menu-item class="nav-item">登录</el-menu-item>
                    </el-col>
                </el-row>
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
     background:none;
     width: 100%;
     border: 0;
     .nav-item{
         color: white;
        text-align: center;
     }
 }
</style>