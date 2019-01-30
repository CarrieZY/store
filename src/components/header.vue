<template>
    <div class="header">
        <div class="header-main">
            <div class="logo">STORE</div>
            <div class="content">
                <span>登录</span>
                <span>注册</span>
                <span>关于</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.header{
    width:100%;
    height:45px;
    line-height: 45px;
    background:#333;
    color:#fff;
}
.header-main{
    max-width: 1200px;
    margin:0 auto;
}
.logo{
    float:left;
    font-size: 20px;
    font-weight: 700;
    color:blueviolet;
}
.content{
    float:right;
    font-size: 16px;
}
.content span{
    margin-right:20px;
}
</style>
