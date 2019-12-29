<template>
<!-- <v-app> -->
  <div>
      <ul>
         <router-link to="/comingsoon"> <li>Products</li> </router-link>
         <router-link to="/comingsoon"> <li>Partners</li></router-link>
         <router-link to="/comingsoon"><li>About Us</li></router-link>
         <router-link to="/comingsoon"><li>Contact Us</li></router-link>
         
      </ul>
  </div>
<!-- <v-spacer></v-spacer> -->


<!-- </v-app> -->
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

.v-btn {
    display: inline-block;
}
li{
    list-style-type: none;
    color: black;
    margin-top: 4px;
    cursor:pointer;
}

</style>
