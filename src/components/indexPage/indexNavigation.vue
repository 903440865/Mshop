<template>
    <div>
        <div class="icons">
            <div class="icons-content">
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/bda58ffc3016edad84e656e8a94b0321.png" alt="">
                    </div>
                    <p class="icon-desc">便宜捡漏</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://img1.qunarzz.com/piao/fusion/1804/ff/fdf170ee89594b02.png" alt="">
                    </div>
                    <p class="icon-desc">捉妖联盟</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://img1.qunarzz.com/piao/fusion/1803/a6/6d97515091789602.png" alt="">
                    </div>
                    <p class="icon-desc">拍卖场</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://img1.qunarzz.com/piao/fusion/1803/50/26ffa31b56646402.png" alt="">
                    </div>
                    <p class="icon-desc">清爽夏日</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://img1.qunarzz.com/piao/fusion/1803/b6/37560ece9c62b502.png" alt="">
                    </div>
                    <p class="icon-desc">欢乐城堡</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20195/b0026eb6f96fd2daecba0d7982c7e4c8.png" alt="">
                    </div>
                    <p class="icon-desc">砍票基地</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://img1.qunarzz.com/piao/fusion/1803/3e/86314b2af03b7502.png" alt="">
                    </div>
                    <p class="icon-desc">飞机场</p>
                </div>
                <div class="icon">
                    <div class="icon-img">
                        <img class="icon-imgcontent" src="http://img1.qunarzz.com/piao/fusion/1803/b1/528a9e80403b8c02.png" alt="">
                    </div>
                    <p class="icon-desc">全部分类</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'indexNavigation'
}
</script>

<style scoped lang="stylus">
.icons
    overflow:hidden
    height:0
    padding-bottom:55%
    padding-left: .3rem
    padding-right: .3rem
    border-bottom-right-radius: .3rem
    border-bottom-left-radius: .3rem;
    background:yellow
    .icons-content
        padding-bottom:50%
        border-radius:0.2rem
        background:white
        .icon
            position :relative
            overflow :hidden
            float:left
            width:25%
            height:0
            padding-bottom:25%
            border-radius:0.2rem
            .icon-img
                position :absolute
                top:0
                left:0
                right:0
                bottom:.44rem
                box-sizing:border-box
                padding:.1rem
                .icon-imgcontent
                    display :block
                    margin :0 auto
                    height:100%
            .icon-desc
                position :absolute
                left:0
                right:0
                bottom:0
                text-align:center
                line-height:.44rem
                height:.44rem
                color:#7B7B7B

</style>
