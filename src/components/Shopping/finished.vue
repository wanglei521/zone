<template>
  <div class="finshied">
    <div class="finished-all">
        <div class="header">
			<a href="javascript:history.back(-1);"></a>
			<span class="forget">订单已完成</span>
        </div>
        <div class="bottom">
			<a href="#/home" class="a1">返回首页</a>
			<a class="a2" href="#/mydd">查看我得订单</a>
        </div>
    </div>

  </div>
</template>
<script>
import {setCookie,getCookie} from '../../assets/js/cookie.js'
import qs from 'qs'
export default {
  data () {
    return{

    }
  },
  mounted(){

  },
  methods:{

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .finshied{width:100%;height:100%;background:url(../../images/finishied.png)no-repeat;background-size:cover;}
    .finished-all {max-width:640px;margin:0 auto;height:100%;}
    .header{height: 0.88rem;padding-left: 0.28rem;position:relative;padding-top: 0.3rem;}
    .header a{width: 0.18rem;height: 0.34rem;display: block;background: url(../../images/backw.png) no-repeat;background-size: cover;float:left;margin-top:0.27rem;}
    .forget{line-height:0.88rem;font-size:0.34rem;display:block;float:left;color: #fff;position: absolute;left: 50%;-webkit-transform: translateX(-50%);-moz-transform: translateX(-50%);-ms-transform: translateX(-50%);-o-transform: translateX(-50%);transform: translateX(-50%);}

    .bottom{height:0.7rem;position:absolute;bottom:0.34rem;left:0.55rem;}
    .bottom a{height:0.93rem;width:2.65rem;display:block;float:left;text-align:center;line-height:0.7rem;font-size:0.23rem;}
    .bottom .a1{background: url(../../images/a1.png) no-repeat;background-size:cover;color:#018dd3;}
    .bottom .a2{background: url(../../images/a2.png) no-repeat;background-size: cover;color:#fdfeff;}
</style>
