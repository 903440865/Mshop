<template>
    <div class="all">
        <div class="logo">
            <div class="iconfont arrow-icon">&#xe64f;</div>
        </div>
        <div class="search">
            <span class="iconfont">&#xe60d;</span>
            输入你想要的宝贝
        </div>
        <div class="scan">
            <div class="iconfont arrow-icon">&#xe661;</div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'indexHeader'
}
</script>

<style scoped>
.all{
    display:flex;
    height:.86rem;
    background-color:yellow;
}   
.logo{
    width:1rem;
    float :left;
    line-height: .86rem;
    text-align: center;
}
.arrow-icon{
    font-size: .5rem;
}
.search{
    flex:1;
    height:.64rem;
    line-height: .64rem;
    margin-top: .12rem;
    background-color:#fff;
    border-radius: .1rem; 
    padding-left: .2rem;  
    color: #ccc; 
}
.scan{
    width:1rem;
    float:right;
    line-height: .86rem;
    text-align: center;
}
</style>
