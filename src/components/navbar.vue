<template>
  
    <v-app-bar
      app
      color="white"
      flat
    >
    
      <div class="d-flex align-center">
        <router-link to="/">
        <v-img
          alt="Gateguard Logo"
          class="shrink ml-5 "
          contain
          src="../../public/Logo.png"
          transition="scale-transition"
          width="150"
          height="150"
        />
        </router-link>
        
      </div>

      <v-spacer></v-spacer>

      <div class="nav"> 
       <router-link to="/comingsoon">
      <v-btn
        
       text
      >

        <span class="ml-5">Products</span>
        
      </v-btn>
        </router-link>

       <router-link to="/comingsoon">
      <v-btn
       
        text
      >
        <span class="ml-5">Partners</span>
      
      </v-btn>
       </router-link>

       <router-link to="/comingsoon">
      <v-btn
        
        text
      >
        <span class="ml-5">About Us</span>
       
      </v-btn>
       </router-link>

       <router-link to="/comingsoon">
      <v-btn
        
        text
      >
        <span class="ml-5">Contact Us</span>
      </v-btn>
       </router-link>

       <v-btn small color="#49A347" class="white--text ml-5 ">Login</v-btn>
       <v-btn small outlined  color="#49A347" class="text--white ml-5">Download</v-btn>
       </div>
    </v-app-bar>

</template>

<script>


export default {
  name: 'App',
  //  components:{ Navbar },
 

  data: () => ({
    drawer: false,
      group: null,
    icon: [
        // {name: 'uu', pic:'./Logo.png'},
    ]
  }),
};
</script>
<style >
a{
   text-decoration: none;
}
.nav{
  margin-left: 200px;
}

</style>
