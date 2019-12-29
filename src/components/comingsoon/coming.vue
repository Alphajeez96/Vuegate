<template>
   <div id="ff">
       <div class="wrapper">
  <h1 class="white--text pb-5">coming soon<span class="dot">...</span></h1>
  
  <p class="white--text"></p>
  <div class="icons pt-5">

  
    <!-- <a href=""><i class="fa fa-youtube-play"></i></a>
    <a href=""><i class="fa fa-paper-plane"></i></a> -->

     <a href="https://twitter.com/p_chukwudire" target="_blank"><v-icon>mdi mdi-twitter</v-icon> </a>
   <a href="mailto:'chimeremezechukwudire@gmail.com'"><v-icon>mdi mdi-mail</v-icon></a>
     <a href="https://web.facebook.com/chimeremeze.chukwudire " target="_blank"><v-icon>mdi mdi-facebook</v-icon></a>

  </div>
 </div>
   </div>

</template>

<style scoped>
    #ff{
        background:#00091B;
        height: 100%
    }
    @keyframes fadeIn {
  from {top: 20%; opacity: 0;}
  to {top: 100; opacity: 1;}
  
}

@-webkit-keyframes fadeIn {
  from {top: 20%; opacity: 0;}
  to {top: 100; opacity: 1;}
  
}

.wrapper {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
  animation: fadeIn 1000ms ease;
  -webkit-animation: fadeIn 1000ms ease;
  
}

h1 {
  font-size: 50px;
  font-family: 'Poppins', sans-serif;
  margin-bottom: 0;
  line-height: 1;
  font-weight: 700;
}

.dot {
  color: #4FEBFE;
}

p {
  text-align: center;
  margin: 18px;
  font-family: 'Muli', sans-serif;
  font-weight: normal;
  
}

.icons {
  text-align: center;
  display:flex-inline;
  
}
a{
  text-decoration: none
}

.icons i {
  color: #00091B;
  background: #fff;
  height: 15px;
  width: 15px;
  padding: 13px;
  margin: 0 10px;
  border-radius: 50px;
  border: 2px solid #fff;
  transition: all 200ms ease;
  text-decoration: none;
  position: relative;
}

.icons i:hover, .icons i:active {
  color: #fff;
  background: none;
  cursor: pointer !important;
  transform: scale(1.2);
  -webkit-transform: scale(1.2);
  text-decoration: none;
  
}

</style>