<template>
	<div class="ykj">
       <h2>挖矿就选原链云矿机</h2>
       <p>原链云矿机是官方定制的一款云矿机，零成本、零设备、零电费投入，保证算力每天86400秒为你挖矿综合年产率13.07%-43.2%，你挖矿的不二选择</p>
       <div class="ykj-content">
       	    <div class="ykj-icon1"><img src="../assets/1.png" alt=""></div>
       	  	<div class="ykj-icon2"><img src="../assets/2.png" alt=""></div>
       	  	<div class="ykj-icon3"><img src="../assets/3.png" alt=""></div>
       	  	<div class="ykj-icon4"><img src="../assets/4.png" alt=""></div>
       	  	<div class="ykj-icon5"><img src="../assets/5.png" alt=""></div>
       	  	<div class="ykj-icon6"><img src="../assets/6.png" alt=""></div>
       	  	<div class="ykj-center"><img src="../assets/中心图.png" alt=""></div>
       	  <div class="ykj-content-c1">
       	  	<li class="cir1"><img src="../assets/跑动圆点.png" alt=""></li>
       	  	<div class="ykj-content-c2"><li class="cir2"><img src="../assets/跑动圆点.png" alt=""></li></div>
       	  </div>
       </div>
    </div>
</template>

<script>
export default {
  name: 'ContentOne',

};
</script>

<style scoped>
li{
	list-style: none;
	position: absolute;
}
.content-body{
	width: 1200px;
	margin: 0 auto;	
}
.ykj{
  height: 884px;
  width: 100%;
}
.ykj-content{
	position: relative;
	top: 100px;
	width: 550px;
	height: 550px;
	margin:0 auto;
}
.ykj-content-c1{
	width: 550px;
    height: 550px;
    border: 2px dashed #c6d7ed;
    border-radius: 300px;
}
.ykj-icon1,.ykj-icon2,.ykj-icon3,.ykj-icon4,.ykj-icon5,.ykj-icon6,.ykj-center{
	position: absolute;
	
}
.ykj-center{
	top:60px;
	left:60px;
}
.ykj-icon1{
    top: 200px;
    left: -40px;
}
.ykj-icon2{
    top: 0px;
    left: 100px;
}
.ykj-icon3{
    top: 0px;
    left: 350px;	
}
.ykj-icon4{
    top: 470px;
    left: 350px;	
}
.ykj-icon5{
    top: 470px;
    left: 100px;
}
.ykj-icon6{
    top: 200px;
    right: -40px;
}
.cir1{
    top: 90px;
    right: 50px;
}
.cir2{
    top: 130px;
    right: 53px;
}
.ykj-content-c2{
	margin:25px auto;
	width: 500px;
    height: 500px;
    border: 2px dashed #d5e1f2;
    border-radius: 300px;
}
.ykj h2{
  margin-top: 82px;
}
.ykj p{
  margin: 47px auto 0;
  font-size: 16px;
  width: 920px;
  height: 43px;
  line-height: 30px;
}
</style>
