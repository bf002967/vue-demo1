<template>
    <div class="footer">
        <div class="content-body">
            <div class="footer-logo">LOGO</div>
            <div class="footer-link">
              <p>社区</p>
              <ul>
                <a href="#"><li>Reddit</li></a> 
                <a href="#"><li>巴比特</li></a>  
                <a href="#"><li>Bitcointalk</li></a>  
                <a href="#"><li>Twitter</li></a>  
              </ul>
            </div>
        </div>    
    </div>
</template>

<script>
export default {
  name: 'mFooter',

  };
</script>

<style scoped>
.content-body{
	width: 1200px;
	margin: 0 auto;	
}
.footer{
  width: 100%;
  height: 370px;
  background:#1f2026;
}
.footer-logo{
  margin-top: 140px;
  float: left;
  color: #fff;
  width: 60%;
}
.footer-link{
  margin-top: 120px;
  float: left;

}
.footer-link p{
  margin-left:10px; 
  color: #fff;
  font-size: 20px;
}
.footer-link a{
  text-decoration: none;
  color: #fff;
}

.footer-link li{
  font-size: 14px;
  color: #666;
  line-height: 28px;
  text-align: left;
  list-style: none;
}
</style>
