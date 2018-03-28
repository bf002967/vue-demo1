

<template>
	
	<div class="buy-type">
	<div class="content-body">
      <div class="exp-machine">
      	<div class="exp-machine-ykj">
      	  <div class="ykj-content">
      		<div class="exp-machine-header">
      			<img src="../assets/矿机图标.png" alt="">
      			<h2>体验云矿机N030型</h2>
      		</div>
      		<hr>
      		<div class="exp-machine-content">
      			<div class="exp-machine-content-w">
      				<ul class="w-list">
      					<li>矿机型号：</li>
      					<li>周期：</li>
      					<li>预期年化：</li>
      					<li>数量：</li>
      				</ul>
      				<ul class="w-cont">
      					<li>N030</li>
      					<li>30天</li>
      					<li style="color: #ff6600;font-size: 24px;">180%</li>
      					<li>含100个YCC</li>
      				</ul>
      			</div>
      			<div class="exp-machine-content-w">
      				<ul class="w-list">
      					<li>产量：</li>
      					<li>奖励：</li>
      					<li>收益：</li>
      					<li>价格：</li>
      				</ul>
      				<ul class="w-cont">
      					<li>0.033个YCC/每天</li>
      					<li>0.047个YCC/每天</li>
      					<li style="color: #ff6600">0.5个YCC/每天</li>
      					<li style="color: #ff6600">100元</li>
      				</ul>      				
      			</div>
      		</div>
      		<div class="exp-machine-footer">
      			<p>注：所有矿工均有一次体验机会</p>
      			<a href="#"><button class="exp-btn" style="cursor: pointer;">立即领取</button></a>
      		</div>
      	  </div>
      	</div>
      	
      		<div class="kf2wm">
      		   <div class="kf2wm-pic"><img src="../assets/矿机客服大2.png" alt=""></div>
      		   <h3>微信客服二维码</h3>
      		   <p>联系客服，了解矿机资源。</p>
      	    </div>
        
      </div>
      <div class="machine-hr">
         <hr><h3>热销机型</h3><hr>
         <p>目前为预售阶段，即将上线，请联系客服，了解矿机资源。</p>
      </div>
		<!-- 热销机型 -->
	  <div class="hot-machine">	
        <a href="#">
        <div class="hot-type hot1">
          <div class="cloudhost-icon-2">
            <img src="../assets/矿机图标.png" alt="">
          </div>
          <p class="machine">云矿机A型</p>
          <p class="date">挖矿周期90-360天</p>
          <p class="require">A型需获取邀请码或升级获取资格</p>
        </div>
        </a>
        <a href="#">
        <div class="hot-type">
          <div class="cloudhost-icon-2">
            <img src="../assets/矿机图标.png" alt="">
          </div>
          <p class="machine">云矿机B型</p>
          <p class="date">挖矿周期90-360天</p>
          <p class="require">B型需获取邀请码或升级获取资格</p>
        </div>
        </a>
        <a href="#">
        <div class="hot-type">
          <div class="cloudhost-icon-2">
            <img src="../assets/矿机图标.png" alt="">
          </div>
          <p class="machine">云矿机C型</p>
          <p class="date">挖矿周期90-360天</p>
          <p class="require">C型需获取邀请码或升级获取资格</p>
        </div>
        </a>
      </div>
    </div>
    </div>
</template>

<script>
export default {
  name: 'ContentTwo',

};
</script>

<style scoped>
ul{
	float: left;
}
li{
	list-style: none;
}
a:visited{
	color: #000;
}
.content-body{
	height: 843px;
	width: 1200px;
	margin: 0 auto;	
}
.exp-machine{
	height: 400px;
}
.hot-machine{
	height: 400px;

}
.exp-machine-ykj{
	float: left;
    position: relative;
    top: 50px;
	width: 793px;
	height: 355px;
	background-color: #ffffff;
	box-shadow: 0px 5px 4px 0px 
	rgba(0, 0, 0, 0.1);
}
.exp-machine-ykj hr{
	width: 700px;
	height: 3px;
	border: none;
	background-image: linear-gradient(90deg, 
		#2086ee 0%, 
		#40e4d5 100%), 
	linear-gradient(
		#cccccc, 
		#cccccc);
	background-blend-mode: normal, 
		normal;
}
.ykj-content{
	width: 700px;
	margin: 0 auto;

}
.exp-machine-header{
	height: 90px;
}
.exp-machine-header img{
	float: left;
	margin-top: 20px;
}
.exp-machine-header h2{
	float: left;

	margin-top: 35px;
}
.exp-machine-content{
	height: 180px;
}
.w2{
	margin-left: 200px;
}
.exp-machine-content-w{
	width: 350px;
	float: left;

}
.w-list,.w-cont{
	float: left;
	text-align: left;
}
.w-list li{
	font-size: 16px;
	font-weight: bold;
	line-height: 38px;	
}
.w-cont li{
	font-size: 16px;
	line-height: 38px;	
}

.exp-machine-footer p{
	display: inline-block;
	float: left;
}
.exp-btn{
	display: inline-block;
	width: 110px;
	height: 35px;
	background-image: linear-gradient(90deg, #2086ee 0%, #40e4d5 100%), 
	linear-gradient(#cb2929, #cb2929);
	background-blend-mode: normal, normal;
	border: none;
	color: #fff;
	float: right;
}
.kf2wm{
	float: left;
	position: relative;
	top: 50px;
	left: 27px;
	width: 379px;
	height: 355px;
	background-color: #ffffff;
	box-shadow: 0px 5px 4px 0px 
	rgba(0, 0, 0, 0.1);
}
.kf2wm-pic{
	margin-top: 30px;
}
.machine-hr{
	margin-top: 50px;
}
.machine-hr hr{
	display: inline-block;
	width: 520px;
	color: #999;
}
.machine-hr h3{
	display: inline-block;
	margin: 0 20px;
    font-size: 24px;

}
.buy-type{
  width: 100%;
  height: 843px;
  background: #ebeff1;
}
.hot-type{
  width: 380px;
  height: 262px;
  margin-top: 0;
  float: left;
  margin-left: 28px;
  background-color: #ffffff;
  box-shadow: 0px 5px 4px 0px 
  rgba(0, 0, 0, 0.1);
}
.hot1{
	margin-left: 0;
}
.machine{
  width: 130px;
  height: 23px;
  margin: 20px auto 16px;
  font-family: PingFang-SC-Bold;
  font-size: 24px;
  font-weight: normal;
  font-stretch: normal;
  line-height: 26px;
  letter-spacing: 0px;
  color: #333333;
}
.date{
  width: 120px;
  height: 14px;
  margin: 0 auto;
  font-family: PingFang-SC-Regular;
  font-size: 14px;
  font-weight: normal;
  font-stretch: normal;
  line-height: 26px;
  letter-spacing: 0px;
  color: #333333;
}
.require{
  width: 206px;
  height: 14px;
  margin: 27px auto 0;
  font-family: PingFang-SC-Bold;
  font-size: 14px;
  font-weight: normal;
  font-stretch: normal;
  line-height: 26px;
  letter-spacing: 0px;
  color: #ff6600;  
}
.cloudhost-icon-2{
  margin: 33px auto 0;
  width: 57px;
  height: 58px;
}

</style>
