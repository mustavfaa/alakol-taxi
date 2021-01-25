<template>
  <div >

    <footer class="karkas-razdela">
  <div class="container">
  <div class="karkas-cta pt-5 pb-5">
  <div class="row">
  <div class="col-xl-4 col-md-4 mb-30">
  <div class="singulon-kudesa">
  <i class="fas fa-map-marker-alt" style="color: #FFD700;"></i>
  <div class="opisaniye_teksta">
  <h4>Найди нас</h4>
  <span>Восточный Казахстанский область.<br> Урджарский район. Алаколь</span>
  </div>
  </div>
  </div>
  <div class="col-xl-4 col-md-4 mb-30">
  <div class="singulon-kudesa">
  <i class="fas fa-phone" style="color: #FFD700;"></i>
  <div class="opisaniye_teksta">
  <h4>Позвоните нам</h4>
  <span>+7(705) 795 5073</span>
  </div>
  </div>
  </div>
  <div class="col-xl-4 col-md-4 mb-30">
  <div class="singulon-kudesa">
  <i class="far fa-envelope-open" style="color: #FFD700;"></i>
  <div class="opisaniye_teksta">
  <h4>Напишите нам</h4>
  <span>ZorNet@info.Ru</span>
  </div>
  </div>
  </div>
  </div>
  </div>
  <div class="karkas-content pt-5 pb-5">
  <div class="row">
  <div class="col-xl-4 col-lg-4 ">
  <div class="karkas-widget">
 
  
  <div class="karkas-social-icon" style="">
  <span>Подписывайтесь на нас</span>
  <a href="#"><i class="fab fa-facebook-f facebook-bg"></i></a>
  <a href="#"><i class="fab fa-twitter twitter-bg"></i></a>
  <a href="#"><i class="fab fa-google-plus-g google-bg"></i></a>
  <a href="#"><i class="fab fa-facebook-f twitter-bg"></i></a>
  <a href="#"><i class="fab fa-google-plus-g google-bg"></i></a>
  </div>
  </div>
  </div>
  
  
  
  </div>
  </div>
  </div>
  <div class="copyright-area">
  <div class="container">
  <div class="row">
  <div class="col-xl-6 col-lg-6 text-center text-lg-left">
  <div class="avtorskiye-teksty">
  <p>Copyright © 2021, ALAKOL TOURIST TAXI </p>
  </div>
  </div>
  <div class="col-xl-6 col-lg-6 d-none d-lg-block text-right">
  <div class="karkas-navigatsiya">
  <ul>
  <li><a href="#">Главная</a></li>
  <li><a href="#">Услуги</a></li>
  <li><a href="#">Контакты</a></li>
  <li><a href="#">Алаколь</a></li>
  
  </ul>
  </div>
  </div>
  </div>
  </div>
  </div>
  </footer>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css">
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
.karkas ul {
  margin: 0px;
  padding: 0px;
}
.karkas-razdela {
  background: #151414;
  position: relative;
}
.karkas-cta {
  border-bottom: 1px solid #373636;
}
.singulon-kudesa i {
  color: #ff5e14;
  font-size: 30px;
  float: left;
  margin-top: 8px;
}
.opisaniye_teksta {
  padding-left: 15px;
  display: inline-block;
}
.opisaniye_teksta h4 {
  color: #f9f3f3;
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 2px;
}
.opisaniye_teksta span {
  color: #757575;
  font-size: 15px;
}
.karkas-content {
  position: relative;
  z-index: 2;
}
.karkas-pattern img {
  position: absolute;
  top: 0;
  left: 0;
  height: 330px;
  background-size: cover;
  background-position: 100% 100%;
}
.karkas-logo {
  margin-bottom: 10px;
}
.karkas-logo img {
  max-width: 285px;
  max-height: 60px;
}
.karkas-text p {
  margin-bottom: 14px;
  font-size: 14px;
  color: #7e7e7e;
  line-height: 28px;
}
.karkas-social-icon span {
  color: #f9f3f3;
  display: block;
  font-size: 20px;
  font-weight: 700;
  font-family: 'Poppins', sans-serif;
  margin-bottom: 20px;
}
.karkas-social-icon a {
  color: #f9f3f3;
  font-size: 16px;
  margin-right: 15px;
}
.karkas-social-icon i {
  height: 40px;
  width: 40px;
  text-align: center;
  line-height: 38px;
  border-radius: 50%;
}
.facebook-bg{
  background: #3B5998;
}
.twitter-bg{
  background: #55ACEE;
}
.google-bg{
  background: #DD4B39;
}
.karkas-widget-heading h3 {
  color: #f9f3f3;
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 40px;
  position: relative;
}
.karkas-widget-heading h3::before {
  content: "";
  position: absolute;
  left: 0;
  bottom: -15px;
  height: 2px;
  width: 50px;
  background: #ff5e14;
}
.karkas-widget ul li {
  display: inline-block;
  float: left;
  width: 50%;
  margin-bottom: 12px;
}
.karkas-widget ul li a:hover{
  color: #ff5e14;
}
.karkas-widget ul li a {
  color: #878787;
  text-transform: capitalize;
}
.podpisasya_forma {
  position: relative;
  overflow: hidden;
}
.podpisasya_forma input {
  width: 100%;
  padding: 14px 28px;
  background: #2E2E2E;
  border: 1px solid #2E2E2E;
  color: #f9f3f3;
}
.podpisasya_forma button {
  position: absolute;
  right: 0;
  background: #cea616;
  padding: 13px 20px;
  border: 1px solid #de6c37;
  top: 0;
}
.podpisasya_forma button i {
  color: #f9f8f7;
  font-size: 22px;
  transform: rotate(-6deg);
}
.copyright-area {
  background: #0e0e0e;
  padding: 25px 0;
}
.avtorskiye-teksty p {
  margin: 0;
  font-size: 14px;
  color: #878787;
}
.avtorskiye-teksty p a{
  color: #e8a612;
}
.karkas-navigatsiya li {
  display: inline-block;
  margin-left: 20px;
}
.karkas-navigatsiya li:hover a{
  color: #ff5e14;
}
.karkas-navigatsiya li a {
  font-size: 14px;
  color: #878787;
}


</style>
