<template>
  <v-app>
    <div>
      
   <v-app-bar-nav-icon @click="shownav = !shownav" id="navigation-icon" class="d-flex d-sm-none d-none d-sm-flex d-md-none "></v-app-bar-nav-icon>
   <router-link to="/"><img class="moblog d-flex d-sm-none d-none d-sm-flex d-md-none " src="../public/Logo.png"></router-link>
   <mobnav :class="{'open':shownav}" class="d-flex d-sm-none d-none d-sm-flex d-md-none "></mobnav>
     <Navbar  class="d-none d-sm-none d-md-flex d-sm-flex"></Navbar>

    <v-content>
       <router-view> </router-view>
    
    </v-content>
   <gfoot></gfoot>
    </div>
  </v-app>
</template>

<script>
import Navbar from '@/components/navbar';
import gfoot from '@/components/footer';
import mobnav from '@/components/mobilenav';



export default {
   data: () => {
   return {
     mobileview:true,
     shownav:false
   }
  },
  methods: {
    handleview() {
      this.mobileview = window.innerwidth <= 990;
    }
  },
  name: 'App',

  components: {
    Navbar, gfoot, mobnav
  },
  Created() {
    this.handleview();
  }

 
};
</script>
<style>

  body{
    overflow: hidden;
  }
  #navigation-icon{
    padding: 10px 20px 0px ;
    /* margin-right: 10px; */
    cursor: pointer;
    /* float:right; */
  }
  .moblog{
    float: right;
    height:5vh;
    /* width:120px; */
    /* padding-bottom: 0px */
    margin-right:5px;

  }
  .open {
   transform: translateX(300px);
  }
</style>



