<template>
	<div class="content-body">
    <div class="buy-procedure">
        <h1 class="buy-title">原链云矿机预定流程</h1>
        <div class="buy-content">
            <div class="buy-path">
          	   <div class="path-1"><p>01</p></div>
          	   <div class="line"></div>
          	   <div class="path-2"><p>02</p></div>
          	   <div class="line"></div>
          	   <div class="path-3"><p>03</p></div>
            </div>
            
        </div>
        <div class="buy-path-word">
        	<div class="word-content">
        		<h3>联系客服</h3>
        		<p>扫描客服二维码<br>联系客服</p>
        	</div>
        	<div class="word-content">
        		<h3>选择机型</h3>
        		<p>与客服沟通<br>需要预定的矿机型号，支付定金</p>
        	</div>            	
        	<div class="word-content">
        		<h3>等待上线</h3>
        		<p>预订成功<br>等待上线获取挖矿收益。</p>
        	</div>
        </div>
    </div>
    </div>
</template>

<script>
export default {
  name: 'ContentThree',

};
</script>

<style scoped>
.content-body{
	width: 1200px;
	margin: 0 auto;	
}
.buy-procedure{
  width: 100%;
  height: 400px;
  background:#fff;
}
.buy-title{
	margin: 80px auto 0;
	width: 240px;
	height: 23px;
	font-family: PingFang-SC-Bold;
	font-size: 24px;
	font-weight: bold;
	font-stretch: normal;
	line-height: 26px;
	letter-spacing: 0px;
	color: #333333;
}
.buy-content{
	margin: 95px auto 0;
	width: 950px;
	height: 90px;

}
.buy-path-word{
	margin:0 auto;
	width: 1230px;
	height: 90px;
}
.path-1,.path-2,.path-3{
	width: 80px;
	height: 80px;
	border-radius: 50px;
	background-image: linear-gradient(90deg, #2086ee 0%, #40e4d5 100%), 
	linear-gradient(#f1f4f4, #f1f4f4);
	background-blend-mode: normal, normal;
}
.path-1 p,.path-2 p,.path-3 p{
	position: relative;
    left: 25px;
	width: 29px;
	height: 23px;
	font-family: PingFang-SC-Bold;
	font-size: 30px;
	font-weight: normal;
	font-stretch: normal;
	line-height: 26px;
	letter-spacing: 0px;
	color: #ffffff;
}
.line{
	margin-top: 35px;
	width: 273px;
	height: 3px;
	background-image: linear-gradient(90deg, #2086ee 0%, #40e4d5 100%), 
	linear-gradient(#cccccc, #cccccc);
	background-blend-mode: normal, normal;
}
.path-1,.path-2,.path-3,.line{
	float: left;
	margin-left: 27px;
}
.word-content{
	width: 32.5%;
	float: left;

}
.word-content p{
    color: #555;
    font-family: PingFang-SC-Regular;
}


</style>
