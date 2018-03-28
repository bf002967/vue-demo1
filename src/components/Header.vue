<template>
    <div class="bg-top">
      <div class="bg-top-nav">
        <div class="band"><span>LOGO</span>YUANCHAIN</div>
        <ul class="nav-bar">
          <a href="#"><li>首页</li></a>
          <a href="#"><li>白皮书</li></a>
          <a href="#"><li>技术特色</li></a>
          <a href="#"><li>应用场景</li></a>
          <a href="#"><li>顾问介绍</li></a>
          <a href="#"><li>云矿机</li></a>
        <div class="nav-msg">商务合作邮箱：yuanchain@yuan.org <span>中文</span></div>
        </ul>
      </div>
          <div class="content-body">
            <div>
            	<h1>原链云矿机—火爆预售</h1>
		            <h4>高效节能链上挖矿，挖矿就这么简单</h4>
		            <div class="awm-1"></div>
		            <p>手机扫描二维码预定</p>
		            <div class="awm-2"></div>
		            <p class="p-kf">云矿机限量发售，详情请扫码咨询客服</p>		          
            </div>
          </div>  
        <div class="bg-top-bar"></div>
      <router-view/>
      
    </div>
</template>

<script>
export default {
  name: 'mHeader',

};
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
}
h1{
  color: #fff;
  margin-top: 170px;
}
h4{
  color: #f1f4f4;margin-top: 33px;
}
.content-body{
	width: 1200px;
	margin: 0 auto;
}
.bg-top p{
  color: #f1f4f4;
}
.awm-1{
  margin: 48px auto 17px;
  width: 200px;
  height: 200px;
  background: url(../assets/矿机客服大2.png);
}
.awm-2{
  position: absolute;
  width: 150px;
  height: 150px;
  background: url(../assets/矿机客服小-跟随部分.png);
  z-index: 10005;
  left: 46%;
  top: 750px;
}
.p-kf{
  position: absolute;
  left: 43%;
  top: 870px;
  color: #fff;
}
.bg-top-nav{
  width: 100%;
  height: 60px;

}
.nav-msg{
  float: right;
  margin-right: 120px;
  line-height: 60px;
  color: #fff;
}
.nav-msg span{
  display: inline-block;
  border: 1px solid #fff;
  height: 25px;
  width: 75px;
  vertical-align: middle;
  line-height: 25px;
  margin-left: 25px;
}
.band{
  float: left;
  line-height: 60px;
  color: #fff;
  margin-left: 35px;
}
.band span{
  border: 1px solid #fff;
  text-align: center;
}
.nav-bar{
  margin-left: 200px;
  height: 100%;
  line-height: 60px;
}
.nav-bar a{
  float: left;
  margin-left: 50px;
  text-decoration: none;
}
.nav-bar li{
  list-style: none;
  color: #fff;
  opacity: .9;
  font-size: 14px;
}
.bg-top{
  position: relative;
  margin-top: -60px;
  width: 100%;
  height: 900px;
  background: url(../assets/背景1.png);
}
.bg-top-bar{
  width: 100%;
  height: 88px;
  margin-top: 201px;
  opacity: .9;
  background-color:rgba(219,222,222,.9);

}
</style>
