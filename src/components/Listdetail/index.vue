<template>
    <div class="listcircle">
        <div class="listbanner">
            <div class="header">
                <div class="header-top">
                    <a href="javascript:history.go(-1);"></a>
                    <span class="forget">圈子详情</span>
                    <div class="user"></div>
                    <div class="ld"></div>
                </div>
                <div class="header-bottom">
                    <div class="header-bottom-top">
                        <div class="tip-bottom-l">
                            <img/>
                        </div>
                        <div class="tip-bottom-r">
                            <ul>
                                <li class="li1">
                                    <span class="sp1">1</span>
                                    <div class="sp2">
										<li class="li4">
											<label>
					                            <input type="checkbox"><b></b>
					                        </label>
										</li>
									</div>
                                </li>
                                <li class="li2">1</li>
                            </ul>
                        </div>
                    </div>
                    <div class="header-bottom-bottom">
                        <ul>
                            <li class="li1">成员数：</li><li class="li1">1111111</li>
                            <li class="li2 mt70">帖子数：</li><li class="li1">111111</li>
                            <li class="li3">已加入</li>
                        </ul>
                    </div>
                    <div class="header-bottom-down">这里是本群描述</div>
                </div>
            </div>
        </div>
        <div>
            <div class="nav1">
                <ul class="nav1-tip">
                    <li class="nav1-li1">圈子成员</li>
                    <li class="nav1-li2"></li>
                    <li class="nav1-li3">(共<span>30</span>名成员)</li>
                    
                </ul>
            </div>
            <div class="nav2">
                <div class="nav2-content mt0">
                    <dl>
                        <dt><img src="../../images/banner.png"/></dt>
                        <dd>哈士奇</dd>
                    </dl>
                    <dl>
                        <dt><img src="../../images/yq.png"/></dt>
                        <dd>邀请</dd>
                    </dl>
                </div>
            </div>
        </div>
        <div class="p140">
            <div class="nav1">
                <ul class="nav1-tip">
                    <li class="nav1-li1">圈子介绍</li>
                </ul>
            </div>
            <div class="nav2 bt0">
                <span class="nav2-content h">
                    随着网络规模的不断扩大，网络技术不断发展，如何进行有效的网络维护，让设备在生命周期内得到有
                    效保障是全球网络运营商关随着网络规模的不断扩大，网络技术不断发展，如何进行有效的网络维护，
                    让设备在生命周期内得到有效保障是全球网络运营商关随着网络规模的不断扩大，网络技术不断发展，
                    如何进行有效的网络维护，让设备在生命周期内得到有效保障是全球网络运营商关随着网络规模的不断
                    扩大，网络技术不断发展，如何进行有效的网络维护，让设备在生命周期内得到有效保障是全球网络运
                </span>
            </div>
        </div>
        <my-footer></my-footer>
    </div>
</template>

<script>
import qs from 'qs'
export default {
    name:'listcircle',
        data () {
             return {
                
             };
         },
         
         methods: {
             
         }
    }
</script>
<style scoped>
	label {
		width: 0.3rem;
		height: 0.26rem;
		display: block;
		z-index: 1;
	}
	
	input[type="checkbox"] {
		display: none;
		position: absolute;
	}
	
	input[type="checkbox"]+b {
		position: absolute;
		display: inline-block;
		width: 0.3rem;
		height: 0.26rem;
		cursor: pointer;
		vertical-align: middle;
	}
	
	input[type="checkbox"]:checked+b {
		background: url(../../images/xinred.png)no-repeat;
		background-size: cover;
		border: none;
	}
	.tip-bottom-r .li1 .sp2 {
		width: 0.3rem;
		height: 0.26rem;
		background: url(../../images/xin.png)no-repeat;
		background-size: cover;
		float: right;
		margin-top: 0.1rem;
	}
    .mt70{margin-left:0.7rem;}
    .listcircle{height:100%;position:relative;}
    .listbanner{width:100%;height:4.07rem;margin:0 auto;background:url(../../images/listbanner.png) no-repeat;background-size:cover;}
    .header{width:5.8rem;height: 0.88rem;margin:0 auto;position: relative;}
    .header a{width: 0.18rem;height: 0.34rem;display: block;background: url(../../images/backw.png) no-repeat;background-size: cover;float:left;margin-top:0.27rem;}
    .header-top,.header-bottom{overflow:hidden;}
    
    
    .ld{width:0.26rem;height:0.88rem;float:right;background:url(../../images/ld.png) no-repeat 0 50%;background-size:0.26rem 0.3rem;}
    .user{width:0.25rem;height:0.88rem;float:right;background:url(../../images/xxx.png) no-repeat 0 50%;background-size:0.25rem 0.3rem;margin-left:0.31rem;}
    
    
    .header-bottom{margin-top:0.2rem;color:#fff;}
    .tip-bottom-l{width: 1.08rem;height: 1.08rem;float: left;border-radius:50%;background:pink;}
    .tip-bottom-l img{width: 1.08rem;height: 1.08rem;float: left;border-radius:50%;}
    .tip-bottom-r{float:left;}
    .tip-bottom-r .li1{line-height:0.43rem;font-size: 0.26rem;padding-left: 0.2rem;margin-top:0.18rem;overflow:hidden;}
    .tip-bottom-r .li1 span{display:block;width:4.22rem;}
    .tip-bottom-r .li1 .sp1{line-height:0.43rem;font-size: 0.26rem;float:left;}
    .tip-bottom-r .li1 .sp2{width:0.3rem;height:0.26rem;background:url(../../images/xin.png)no-repeat;background-size:cover;float:right;margin-top:0.1rem;}
    
    .tip-bottom-r .li2{line-height: 0.38rem;font-size: 0.22rem;padding-left: 0.2rem;overflow : hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 2;-webkit-box-orient: vertical;}
    .header-bottom-top{width:5.8rem;overflow:hidden;}
    .header-bottom-bottom{line-height:0.43rem;width:5.8rem;height:0.43rem;margin-top:0.11rem;border-bottom:0.01rem solid #b6effe;font-size:0.2rem;}
    .header-bottom-bottom li{float:left;}
    .header-bottom-bottom .li3{width:0.8rem;height:0.34rem;line-height:0.34rem;cursor:pointer;text-align:center;background:#fff;color:#008dd3;border-radius:0.05rem;float:right;}
    .header-bottom-down{font-size:0.18rem;line-height:0.54rem;}
    
    .forget{line-height:0.88rem;font-size:0.28rem;display:block;float:left;color: #fff;position: absolute;left: 50%;-webkit-transform: translateX(-50%);-moz-transform: translateX(-50%);-ms-transform: translateX(-50%);-o-transform: translateX(-50%);transform: translateX(-50%);}    

    .nav1{overflow:hidden;}
    .nav1 .nav1-tip{width:6rem;margin:0 auto;height:0.78rem;overflow:hidden;border-bottom:0.01rem solid #ebebeb;position:relative;}
    .nav1-li1{font-size:0.26rem;line-height:0.27rem;border-left:0.03rem solid #008dd3;float:left;color:#1a1a1a;padding-left:0.12rem;position:absolute;top:50%;transform:translateY(-50%);}
    .nav1-li2{width:0.24rem;height:0.78rem;background:url(../../images/backright.png) no-repeat right 50%;background-size:0.12rem 0.23rem;float:right;}
    .nav1-li3{font-size:0.18rem;color:#969696;float:right;line-height:0.78rem;}
    .nav2{width:100%;border-bottom:0.01rem solid #ebebeb;font-size:0;}
    .nav2-content{width:6rem;line-height:0.39rem;margin:0 auto;margin-top:0.13rem;display:block;font-size:0.22rem;text-indent: 2em;overflow:hidden;}
    .h{overflow : hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 3;-webkit-box-orient: vertical;}
    .nav2-content dl{float:left;margin:0 0.24rem 0.35rem 0.24rem;}
    .mt0{margin-top:0.35rem;width:6.2rem;}
    .nav2-content dl dt img{width:0.75rem;height:0.75rem;border-radius:50%;display:block;}
    .nav2-content dl dt{margin:0 auto;border: 1px solid #55c2f0;width:0.75rem;height:0.75rem;border-radius:50%;}
    .nav2-content dl dd{text-align:center;text-indent:0;}
    .nav2-sp1,.nav2-sp2{line-height:0.75rem;display:inline-block;}
    .nav2-sp1{margin-left:0.2rem;background:url(../../images/shoucang.png) no-repeat 0 50%;background-size:0.28rem 0.27rem;padding-left:0.32rem;}
    .nav2-sp2{margin-left:0.43rem;background:url(../../images/zan1.png) no-repeat 0 50%;background-size:0.24rem 0.24rem;padding-left:0.3rem;}
    .p140{padding-bottom:1.4rem;}
    .bt0{border:0;}
    
</style>