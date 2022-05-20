<template>

  <div  class="contact" id="contact" >
    <div class="breadcrumb">
      <el-breadcrumb separator-class="el-icon-arrow-right">
        <el-breadcrumb-item to="/">首页</el-breadcrumb-item>
        <el-breadcrumb-item>联系我们</el-breadcrumb-item>
      </el-breadcrumb>
    </div>

    <div class="wrap">
      <div class="main">
        <div class="contact">
          <div class="contact_left">
            <div class="contact_info">
              <h3>HeartBeat365 公司地址</h3>
              <div class="map">
                <iframe width="100%" height="175" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.co.in/maps?f=q&amp;source=s_q&amp;hl=en&amp;geocode=&amp;q=Lighthouse+Point,+FL,+United+States&amp;aq=4&amp;oq=light&amp;sll=26.275636,-80.087265&amp;sspn=0.04941,0.104628&amp;ie=UTF8&amp;hq=&amp;hnear=Lighthouse+Point,+Broward,+Florida,+United+States&amp;t=m&amp;z=14&amp;ll=26.275636,-80.087265&amp;output=embed"></iframe><br><small><a href="https://maps.google.co.in/maps?f=q&amp;source=embed&amp;hl=en&amp;geocode=&amp;q=Lighthouse+Point,+FL,+United+States&amp;aq=4&amp;oq=light&amp;sll=26.275636,-80.087265&amp;sspn=0.04941,0.104628&amp;ie=UTF8&amp;hq=&amp;hnear=Lighthouse+Point,+Broward,+Florida,+United+States&amp;t=m&amp;z=14&amp;ll=26.275636,-80.087265" style="color: #242424;text-shadow: 0 1px 0 #ffffff;text-align: left;font-size: 0.7125em;padding: 5px;font-weight: 600;">View Larger Map</a></small>
              </div>
            </div>
            <div class="company_address">
              <h3>公司信息 :</h3>
              <p>500 xxxx xxx xxxxxx Sit,</p>
              <p>22-56-2-9 xxxxxxxxx,</p>
              <p>中国</p>
              <p>电话:(00) 222 666 444</p>
              <p>传真: (000) 000 00 00 0</p>
              <p>邮件: <a href="mailto:HeartBeat365@mycompany.com">info(at)mycompany.com</a></p>
              <p>关注我们: <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Weibo</a></p>
            </div>
          </div>
          <div class="contact_right">
            <div class="contact-form">
              <h3>联系我们</h3>
              <form method="post" action="contact-post.html">
                <div>
                  <span><label>姓名</label></span>
                  <span><input type="text" ></span>
                </div>
                <div>
                  <span><label>E-MAIL</label></span>
                  <span><input name="userEmail" type="text" class="textbox"></span>
                </div>
                <div>
                  <span><label>手提电话</label></span>
                  <span><input name="userPhone" type="text" class="textbox"></span>
                </div>
                <div>
                  <span><label>您的宝贵意见</label></span>
                  <span><textarea name="userMsg"> </textarea></span>
                </div>
                <div>
                  <span><input type="submit" value="提交"></span>
                </div>
              </form>
            </div>
          </div>
          <div class="clear"></div>
        </div>
      </div>
    </div>
  </div>







</template>

<script>
export default {
  name: "Contact"
}
</script>

<style scoped>

.contact {
  background-color: white;
}
/* 面包屑CSS */

.contact .breadcrumb {
  height: 50px;
  background-color: white;
}
.contact .breadcrumb .el-breadcrumb {
  width: 1225px;
  line-height: 30px;
  font-size: 16px;
  margin: 0 auto;
}

.wrap{
  margin:0 auto;
  width:80%;
  -moz-transition:all .2s linear;
  -webkit-transition:all .2s linear;
  -o-transition:all .2s linear;
  -ms-transition:all .2s linear;
}



.contact{
  display: block;
}
.contact_left {
  float:left;
  margin-right:3.3333%;
  width: 32.3333%;
}
.contact_right {
  float:left;
  width: 63.3333%;
}
.contact_left h3{
  margin-bottom: 2%;
  text-transform: capitalize;
  font-size: 1.5em;
  color: #252525;
  font-weight: 100;
}
.company_address{
  padding-top:10px;
}
.company_address p{
  color: #242424;
  text-shadow: 0 1px 0 #ffffff;
  line-height: 1.8em;
  font-size: 0.8125em;
  font-weight: 600;
}
.company_address p a{
  color: #52ABDF;
  cursor: pointer;
  -webkit-transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -o-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
  text-shadow: 0 1px 0 #ffffff;
}
.company_address p a:hover{
  color: #242424;
}
.map{
  margin: 6% 0 4%;
}
.contact_right h3{
  margin-bottom: 2%;
  text-transform: capitalize;
  font-size: 1.5em;
  color: #252525;
  font-weight: 100;
}
.contact-form{
  position:relative;
  padding-bottom:30px;
}
.contact-form div{
  padding:5px 0;
}
.contact-form span{
  display: block;
  color: #252525;
  text-shadow: 0 1px 0 #ffffff;
  line-height: 1.5em;
  font-size: 0.7825em;
}
.contact-form input[type="text"],.contact-form textarea{
  font-family: 'Open Sans', sans-serif;
  margin-top: 5px;
  padding: 10px;
  display: block;
  width: 98% !important;
  background: rgba(255, 255, 255, 1);
  outline: none;
  color: #555555;
  font-size: 1em;
  border: 1px solid rgb(224, 224, 224);
  -webkit-appearance: none;
}
.contact-form textarea{
  resize:none;
  height:120px;
}
.contact-form input[type="submit"]{
  margin-top: 10px;
  display: inline-block;
  text-transform: uppercase;
  background: #32A2E3;
  font-family: 'Open Sans', sans-serif;
  color: #FFF;
  padding: 15px;
  border: none;
  font-size: 1em;
  transition: 0.5s all;
  -webkit-transition: 0.5s all;
  -moz-transition: 0.5s all;
  -o-transition: 0.5s all;
  outline: none;
  cursor: pointer;
  float: right;
  width: 25% !important;
  -webkit-appearance: none;
}
.contact-form input[type="submit"]:hover{
  background: #228AC6;
}
</style>