<template>
    <div class="circular">
        <my-header title="退圈通知"></my-header>
        <div class="first">
            <div class="nav">
                <div class="nav-user">
                    <img src="../../images/tongzhi.png"/>
                    <ul class="nav-ul1">
                        <li class="ul-li1">张林海</li>
                        <li class="ul-li2"><span class="sp1">男</span><span class="sp2">北京</span><span class="sp3">北京市</span></li>
                        <li class="ul-li3"><span class="sp1">已退出</span><span class="sp2">重庆处生活圈</span></li>
                    </ul>
                    <ul class="nav-ul2">
                        <li class="ul-li1"></li>
                        <li class="ul-li2">昨天</li>
                    </ul>
                </div>
            </div>
        </div>
        <my-footer></my-footer>
    </div>
</template>
<script>
    import qs from 'qs'
    export default {
    name:'first',
        data () {
             return {
                
             };
         },
         mounted(){
             
         },
         methods: {
             
         }
    }
</script>
<style scoped>
  .first{padding-bottom:0.98rem;}
  .nav{width:6rem;margin:0 auto;}
  .nav-user{height:1.62rem;width:100%;border-bottom:0.01rem solid #ebebeb;}
  .nav-user img{width:0.68rem;height:0.68rem;border-radius:50%;display:block;float:left;margin:0.3rem 0.18rem 0 0.1rem;}

  .nav-ul1{float:left;margin-top:0.26rem;}
  .nav-ul1 .ul-li1{line-height:0.39rem;font-size:0.26rem;color:#292929;}
  .nav-ul1 .ul-li2{line-height:0.37rem;font-size:0.20rem;color:#949494;}
  .nav-ul1 .ul-li2 .sp2{margin-left:0.14rem;}
  .nav-ul1 .ul-li2 .sp3{margin-left:0.21rem;}
  .nav-ul1 .ul-li3{line-height:0.37rem;font-size:0.18rem;color:#3d3d3d;}
  .nav-ul1 .ul-li3 .sp2{color:#008dd3;margin-left:0.11rem;}
  .nav-ul2{float:right;height: 100%;}
  .nav-ul2 .ul-li1{width:0.12rem;height:0.24rem;background:url(../../images/backright.png) no-repeat;background-size:0.12rem 0.24rem;margin-top:0.54rem;float:right;}
  .nav-ul2 .ul-li2{font-size:0.18rem;color:#008dd3;margin-top:1.07rem;float:right;}
</style>