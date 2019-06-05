<template>
    <div class="all">
        <div class="logo">
            <div class="iconfont arrow-icon">&#xe64f;</div>
        </div>
        <div class="search">输入你想要的宝贝</div>
        <div class="scan"></div>
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
    width:1.24rem;
    float:right;
    background-color:black;
}
        

</style>
