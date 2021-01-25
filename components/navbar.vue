<template>
<div style="">


	<header  class="hidden-sm hidden-xs" style="">
            <div class="col-12">

                <div id="mainmenu__area" class="mainmenu__area1 sticky-header scroll-header " >

                    
                      <div class="container " >
                        



                          <div class="col-lg-12 col-md-12 " >
                            <div class="row">
                            
                            
                            <div class="col-lg-1 col-md-1" id="colpadding" style="align-self: center;">
                              <div id="alcenter">
                                <div id="padding-text-menu">
                                  <a href="/"  id="color-text-menu">
                                    Главная
                                  </a>
                                </div>
                                
                              </div>
                              
                              
                            </div>
                            <div class="col-lg-1 col-md-1" id="colpadding" style="align-self: center;">
                              <div id="alcenter">
                                <div id="padding-text-menu">
                                  <a href="/new" id="color-text-menu">
                                    Новости
                                  </a>
                                </div>                             
                                
                              </div>
                              
                            </div>
                            <div class="col-lg-1 col-md-1" id="colpadding" style="align-self: center;">
                              <div id="alcenter">
                                <div id="padding-text-menu">
                                  <a href="#" id="color-text-menu">
                                    Контакты
                                  </a>
                                </div>
                                
                              </div>
                              
                              
                            </div>
                            <div class="col-lg-1 col-md-1" id="colpadding" style="align-self: center;">
                              <div id="alcenter">
                                <div id="padding-text-menu">
                                  <a href="/alakol"  id="color-text-menu">
                                    Алаколь
                                  </a>
                              </div>
                            </div>
                              
                              
                            </div>
                            <div class="col-lg-3 col-md-3" id="colpadding">
                              <div class="col-lg-12 col-md-12" id="colpadding">
                                <div class="row">
                                  <div class="col-lg-6 col-md-6" id="colpadding" style="align-self: center;">
                                    <div id="alcenter">
                                      <div id="padding-text-menu">
                                        <a href="/" id="color-text-menu">
                                          Такси на Алакөл
                                        </a>
                                      </div>
                                      
                                    </div>
                                  
                                </div>
                                

                                </div>

                                
                                

                              </div>
                              
                              

                            </div>
                                  



                            <div class="col-lg-5" id="colpadding">
                                  <div >
                                    <a href="/" id="color-text-menu">
                                      <img src="../assets/img/logo21.png" style="width: 80%;float: right;margin-top: 5px;">
                                    </a>
                                  </div>
                                </div>

                                      
                          </div>




                          

                        </div>
                 
                            
                                
                      
                    </div>

                </div>







          
                     

             </div>  



    </header>

    

<header  class="hidden-lg hidden-md" style="">
            <div class="col-12">

                <div id="mainmenu__area" class="mainmenu__area1 sticky-header scroll-header " >

                    
                      <div class="container " >
                        <div class="row">
                          <div class="col-3">
                            <nav id="nav-menu">
                              <i class="material-icons menu" v-on:click="onToggleMenu()" v-if="!menuOpen"  style="color:white;z-index: 1000000 " key="menu">menu</i>
                              
                              


                            </nav>
                          </div>
                          <div class="col-9" id="colpadding" style="padding-right: 10px;">

                            <a href="/" id="color-text-menu">
                              <img src="../assets/img/logo21.png" style="width: 70%;float: right;margin-top:12px;">
                            </a>
                          </div>
                          











                          


                        </div>
                 
                            
                                
                      
                    </div>

                </div>







          
                     

             </div>  



    </header>	
<div id="app">
 
  <div >
      

    
    <header class="header"   v-if="menuOpen">
      
      <div class="navigation" :class="{'open': menuOpen}" >
      <i class="material-icons clear" v-on:click="onToggleMenu()" v-if="menuOpen"  style="color:white;z-index: 1000000;padding: 7px;margin-left: 19px;margin-top: 3px; " key="clear">clear</i>
        <nav >
          <ul style="padding: 0px 0px 0px 0px;">
            <li >
              <a href="/" style="color:white;">Главная</a>
            </li>
            <li >
              <a href="/new" style="color:white;">Новости</a>
            </li>
            <li>
              <a href="/contact" style="color:white;">Контакты</a>
            </li>
            <li>
              <a href="/" style="color:white;">Такси на Алакөл</a>
            </li>

          </ul>
        </nav>
      </div>
    

      

      
    </header>
  </div>


</div> 





</div>





    
    



 
  
</template>
<script>


// register the component
export default {
  name: 'navbar',
  data(){
    return{
      show:false,
      menuOpen: false
    }
    

 

    
  },
  components: {

  },
  
  
  
  props: {
        isOpen: {
          type: Boolean,
          required: false
        },
        right: {
          type: Boolean,
          required: false
        },
        width: {
          type: [String],
          required: false,
          default: '300'
        },
        disableEsc: {
          type: Boolean,
          required: false
        },
        noOverlay: {
          type: Boolean,
          required: false
        },
        onStateChange: {
          type: Function,
          required: false
        },
        burgerIcon: {
          type: Boolean,
          required: false,
          default: true
        },
        crossIcon: {
          type: Boolean,
          required: false,
          default: true
        },
        disableOutsideClick: {
          type: Boolean,
          required: false,
          default: false
        },
        closeOnNavigation: {
          type: Boolean,
          required: false,
          default: false
        }
      },

      methods: {
      goHome(){
        this.$router.push('/')
      },
      goAlakol(){
        this.$router.push('/alakol')
      },
      onToggleMenu () {
        this.menuOpen = !this.menuOpen
      },

      

      



      






    },








  





}
  

</script>

<style >
@import url("https://fonts.googleapis.com/icon?family=Material+Icons");
#colpadding{
  padding-left: 0px;
  padding-right: 0px;
  
}
.bm-menu{
	background-color: #0e0e0e;
}
.bm-burger-button{
    top: 8px;
    left: 15px;
    
}
.bm-burger-bars{
  background-color: #FFD700;
}

#color-text-menu{
  color: #d4d4d4;
  font-size: 13px;
  font-weight: 500;

}
#color-text-menu:hover{

}
.bm-cross{

  background: #FFD700;
}

#padding-text-menu{
  margin: 0px auto;
  align-self: center;}


#alcenter{
  align-self: center;
}





#header{
 
  position: inherit;
    top: auto;
  left: 0;
  margin:100px;
  
  right: 0;
  top: 0;
  width: 100%;
  

 
}
#sticky-header-with-topbar{
background: #ffffff none repeat scroll 0 0;
display: flex;

}
.main__menu {
  display: flex;
  justify-content: center;
}
.main__menu > li > a {
  color: #666666;
  display: block;
  font-size: 14px;
  
  
  position: relative;
  text-transform: capitalize;
}
.main__menu > li {
  padding: 0 20px;
  position: relative;
}
.logo a{
  display: block;
  position: relative;
}
.mainmenu__area {
  
  left: 0;
  margin: auto;
  position: absolute;
  right: 0;
  top: 32px;
  width: 100%;
}

.mainmenu__area .container .row, .mainmenu__area .container-fluid .row {
    display: -webkit-flex;
    display: -moz-flex;
    display: -ms-flex;
    display: -o-flex;
    display: flex;
    -ms-align-items: center;
    align-items: center;
}

.htc-header {
  position: relative;
  z-index: 99;
}

.main__menu > li:hover > a{
  color: #ff4136;
}
.sidebar--content .htc__news__inner {
  margin: 0 auto;
  width: 68%;
}

.header--2 .mean-container a.meanmenu-reveal {
  border: 2px solid #fff;
  color: #fff;
}
.header--2 .mean-container a.meanmenu-reveal span {
  background: #fff none repeat scroll 0 0;
}







/*---------------------------
  Sidebar Menu
----------------------------*/


.sidebar__menu {
    text-align: left;
}

.sidebar__menu li.active{
  background: #fff;
}
.sidebar__menu li.active a{
    color: #ff4136;
}
.sidebar__menu li a {
  display: block;
  font-size: 14px;
  line-height: 30px;
  padding: 0;
  text-align: center;
  text-transform: capitalize;
}
.sidebar__menu--inner {
  padding: 0;
}
.offsetmenu__inner.sidebar__menu--inner {
  height: 100%;
  padding: 0;
}
.sidebar__menu--inner .off__contact .logo {
  padding-top: 40px;
}














/*-------------------------
  Menu Style 7
--------------------------*/

.menu__style--7 .main__menu li.drop:hover ul.dropdown {
  opacity: 1;
  visibility: visible;
  top: 0;
}
.menu__style--7 .main__menu li.drop ul.dropdown {
  background: #ffffff none repeat scroll 0 0;
  box-shadow: 0 0 0 rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.1);
  left: 100%;
  margin: 0;
  opacity: 0;
  padding: 0;
  position:absolute;
  right: auto;
  top: 10px;
  transition: all 0.2s ease-in-out 0s;
  visibility: hidden;
  width: 189px;
  z-index: 99;
}
#mainmenu__area{
  position: fixed;
    top: 0;


}
.sticky-header.scroll-header{
  animation: 300ms ease-in-out 0s normal none 1 running fadeInDown;
  background: #151414;
  box-shadow: 0 0 15px rgba(0, 0, 0,  0.04);
  left: 0;
  margin: 0 auto;
  position: fixed;
  right: 0;
  bottom: 0;
  width: 100%;
  z-index: 99;
  height: 46px;

}


#logo{
  
  
    height: 42px;
    text-align: center;
    /* width: 80px; */
    margin-top: 2px;
}



/*-----------------------------------------
  Sticky  For  Header
-------------------------------------------*/


#sticky-header-with-topbar .logo a {
  height: 50px;
  line-height: 50px;
}
#sticky-header-with-topbar .main__menu > li > a {
  height: 50px;
  line-height: 50px;
}
#sticky-header-with-topbar .menu-extra li a span {
  height: 60px;
  line-height: 62px;
}
#sticky-header-with-topbar .menu-extra li span {
  height: 60px;
  line-height: 62px;
}
.fluid-container.mobile-menu-container {
  position: relative;
}
.mobile-logo {
  align-items: center;
  display: flex;
  height: 52px;
  left: 0;
  padding-left: 15px;
  position: absolute;
  top: 0;
  z-index: 2147483647;
}
.mobile-logo img {
  max-height: 25px;
}

/*-----------------------------
  Dropdown Menu
--------------------------------*/
.main__menu li.drop{
    position: relative;
}
.main__menu li.drop a{
  position: relative;
}
.main__menu li.drop ul.dropdown {
  background: #ffffff none repeat scroll 0 0;
  box-shadow: 0 0 0px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.1);
  left: 0;
  margin: 0;
  opacity: 0;
  padding: 0;
  position: absolute;
  top: 120%;
  transition: all 0.2s ease-in-out 0s;
  visibility: hidden;
  width: 189px;
  z-index: 999;
}
.main__menu li.drop:hover ul.dropdown {
  opacity: 1;
  top: 100%;
  visibility: visible;
}
.header--3 .main__menu li.drop:hover ul.dropdown {
    top: 100%;
}
.main__menu ul.dropdown li {
  border-bottom: 1px solid #f4f4f4;
  display: block;
  position: relative;
}
.main__menu ul.dropdown li a {
  background: #ffffff none repeat scroll 0 0;
  color: #333;
  display: block;
  font-size: 12px;
  font-weight: 700;
  padding: 8px 18px;
  text-align: left;
  text-decoration: none;
  text-transform: uppercase;
  transition: all 0.3s ease 0s;
}
.main__menu li.drop ul.dropdown li:hover > a {
  background: #fafafa none repeat scroll 0 0;
  color: #ff4136;
}
.scroll-header .main__menu li.drop ul.dropdown {
  top: 100%;
}
.scroll-header .main__menu li.drop a:hover ul.dropdown {
  top: 100%;
}



/*----------------------------
  Sub Menu
---------------------------*/

.main__menu li.drop ul.dropdown li.drop::after {
  color: #999;
  content: "";
  font-family: "Material-Design-Iconic-Font";
  font-size: 13px;
  position: absolute;
  right: 20px;
  top: 12px;
  transition: all 0.2s ease-in-out 0s;
}
.main__menu li.drop ul.dropdown li.drop{
  position: relative;
}
.main__menu li.drop ul.dropdown li.drop ul.dropdown.smright {
  border: medium none;
  right: 100%;
  top: 0;
  transition: all 0.3s ease 0s;
}
.main__menu li.drop ul.dropdown li.drop ul.dropdown.level2 {
  border: medium none;
  left: 100%;
  top: 20%;
  transition: all 0.3s ease 0s;
}
.main__menu li.drop ul.dropdown li.drop ul.dropdown.level2 {
    opacity: 0;
    visibility: hidden;
}
.main__menu li.drop ul.dropdown li.drop:hover ul.dropdown.level2 {
    opacity: 1;
    visibility: visible;
    top: 0;
}
.main__menu li.drop ul.dropdown li.drop ul.dropdown.smright {
    opacity: 0;
    visibility: hidden;
}
.main__menu li.drop ul.dropdown li.drop ul.dropdown.smright {
  background: #ffffff none repeat scroll 0 0;
  left: -100%;
  margin: 0;
  opacity: 0;
  padding: 0;
  position: absolute;
  top: 20%;
  transition: all 0.3s ease-in-out 0s;
  visibility: hidden;
  width: 220px;
  z-index: 999;
}
.main__menu li.drop ul.dropdown li.drop:hover ul.dropdown.smright {
  left: -100%;
  opacity: 1;
  visibility: visible;
  top: 0;
}

/*-----------------------------
  Menu Right Side
------------------------------*/


.menu-extra {
    display: flex;
    justify-content: flex-end;
}

.menu-extra li:last-child {
    padding-right: 0;
}
.menu-extra li:first-child {
    padding-left: 0;
}
.menu-extra li span {
    color: #666666;
    font-size: 19px;
    line-height: 30px;
    transition: all 0.3s ease 0s;
    cursor: pointer;
}
.menu-extra li span:hover {
    color: #ff4136;
}
/*---------------------------
  Header Stayle 2
-----------------------------*/












.header {
  background: #151414;
  margin-bottom: 10px;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  position: fixed;
  z-index: 1000;
  height: 100%;
}

.logo {
  color:white;
  font-size: 2em;
  z-index:900;
  position:absolute;
  padding: 10px;
}

.hidden {
  visibility: hidden;
}

.invisible {
  display: none;
}

.menu {
  padding: 10px;
  position: relative;
  z-index: 1000;
}

.menu-hamburger {
  width: 43px;
  height: 30px;
  /*position: absolute;*/
  top: 20px;
  right: 25px;
  margin-left: auto;
  cursor: pointer;
  color: white;
}

.menu-hamburger > .top,
.menu-hamburger > .bottom {
/*   width: 100%; */
  height: 5px;
  background: white;
  margin: 6px auto;
  transition-duration: 0.1s;
}

.menu-hamburger > .middle {
  position: relative;
  background: none;
  text-align: center;
  height: 5px;
  top: -5px;
}

.menu-hamburger > .top.open {
  transform: translate(0px, 11px) rotate(45deg);
}

.menu-hamburger > .middle.open {
  opacity: 0;
}

.menu-hamburger > .bottom.open {
  transform: translate(0px, -11px) rotate(-45deg);
}

.navigation {
  background: #151414;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 900;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.15s;
}

.navigation.open {
  max-height: 300px;
  transition: max-height 0.25s;

}


nav ul {
  list-style: none;
  text-align: center;
  margin: 4em auto;
}


a {
  transition-duration: 0.5s;
  text-decoration: none;
  color: white;
  font-size: 1.5em;
  line-height: 2;
  
}




</style>
