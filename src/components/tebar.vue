<template>
    <section class="tebar-box">
        <router-link to="/" class="tebar-box__btn">
            <i class="iconfont iconhome"></i>
            <div>首页</div>
        </router-link>
        <router-link to="/question" class="tebar-box__btn">
            <i class="iconfont iconproject-copy"></i>
            <div>专题</div>
        </router-link>
        <router-link to="/mine" class="tebar-box__btn">
            <i class="iconfont icongerenzhongxin-denglu"></i>
            <div>我的</div>
        </router-link>
    </section>
</template>
<script>
export default {
    data () {
        return {

        }
    },
    methods: {

    },
    mounted() {
        // console.log(this.$route.path);
    }
}
</script>
<style lang="less">
.tebar-box {
    width: 100%;
    position: fixed;
    bottom: 0; 
    left: 0;
    display: flex;
    border-top: .01rem solid #e1e1e1;
}
.tebar-box__btn {
    width: 33.33%;
    height: .60rem;
    font-size: 0.16rem;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    border-right: .01rem solid #e1e1e1;
    box-sizing: border-box;
    overflow: hidden;
}
.tebar-box__btn:last-child {
    border-right: none;
}
.tebar-box__btn i {
    font-size: .36rem;
}
</style>
