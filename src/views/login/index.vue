<template>
<div class="login">
  <el-input v-model="input" placeholder="请输入内容"></el-input>
</div>
</template>

<script>
export default{
    data(){
        return{
           input: ''
        }
    }
}

</script>

<style lang=scss scoped >
/* .login{ */
    /* background: url(@/assets/imgs/home-bg.jpg); */
/* } */
</style>