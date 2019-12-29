<template>
 <v-app>
   

    <coming></coming>
   <!-- <countdown date="August 15, 2016"></countdown> -->
 



 
  </v-app> 
   
</template>

<script>
// @ is an alias to /src
import coming from '@/components/comingsoon/coming'
// import countdown from '@/components/comingsoon/countdown'


export default {
  components: {
    coming, 
  },
  name: 'home',
  data(){
     return {
      
      }
  }
}

</script>