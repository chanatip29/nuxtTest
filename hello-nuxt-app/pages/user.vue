<template>
  <div>
    <v-btn color="primary" nuxt to="/"> Main </v-btn>

    <div align="center">
      <h1>Uer Index</h1>
      <h2>เเนะนำวิธีการใช้งาน</h2>
    </div>
    
      <v-card>
        <v-card-title class="headline"> ยินดีต้อนรับเข้าสู่ VUE User </v-card-title>
        <v-card-text>
         
          <h2> 
           Name: Chanatip    LastName: Jongviriyajaronechai
          </h2>
          <h2>
            Address : Bkk
            
           
          </h2>
          <h3>
            Phone :
            <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
             092-2970028 </a
            >
          </h3>
          <h3>
           Fackbook :
            <a
              href="https://www.facebook.com/boatLAND/"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              Boat Boat </a
            >
          </h3>
          <h3>
            Thank you for developing with Vuetify and I look forward to bringing
            more exciting features in the future.
          </h3>
          <div class="text-xs-right">
            <em><small>&mdash; Chanatip</small></em>
          </div>
          <hr class="my-3" />
          <a
            href="https://github.com/chanatip29/nuxtTest.git"
            target="_blank"
            rel="noopener noreferrer"
          >
           GitHub
          </a>
          <br />
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt GitHub
          </a>
          
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/"> Back </v-btn>
          <v-btn color="primary" nuxt to="/inspire"> Continue </v-btn>
          
        </v-card-actions>
      </v-card>
    </div>
  
    

   
 
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
