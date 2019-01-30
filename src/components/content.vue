<template>
    <div class="content">
        <div class="left-content">
            <div class="left-nav">
                <p class="title">&nbsp;&nbsp;侧边导航标题</p>
                <ul>
                    <li>子标题</li>
                </ul>
            </div>
        </div>
        <div class="content-inner">

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.content{
    clear: both;
    max-width:1200px;
    margin: 20px auto;
    display: flex;
}
.left-content{
    flex:0 0 300px;
    margin-right:20px;
}
.left-nav{
    width:300px;
    border:1px solid #999;
}
.left-nav .title{
    width:300px;
    height:30px;
    background: #333;
    color:#fff;
    line-height: 30px;
}
.left-nav ul{
    width:300px;
    background: #fff;
}
.left-nav ul li{
    height:20px;
    font-size: 12px;
    color:#333;
    margin-left:20px;
}
.content-inner{
    flex:1;
}
</style>
