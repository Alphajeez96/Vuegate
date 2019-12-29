<template>
 <v-app>
 <div>
    <hero></hero>
    <feature></feature>
    <gateguard></gateguard>
  </div>
  <div>
     <residents></residents>
  </div>
  <section>
    <customers></customers>
  </section>
  <div>
    <download></download>
  </div>
  <div>
    <newsletter></newsletter>
  </div>



 
  </v-app>  
</template>

<script>
// @ is an alias to /src
import hero from '@/components/home/hero'
import feature from '@/components/home/features'
import gateguard from '@/components/home/Gateguard'
import residents from '@/components/home/Residents'
import customers from '@/components/home/customers'
import download from '@/components/home/Download'
import newsletter from '@/components/home/Newsletter'

export default {
  components: {
    hero,feature, gateguard,residents,
    customers, download, newsletter
  },
  name: 'home',
  data(){
     return {
      
      }
  }
}

</script>

