<template>
  <v-app>
    <!-- ----------------------------------------------------------------------------start system bar -->
    <v-system-bar dark height="25px" color="grey lighten-3 ma-0">
      <v-spacer></v-spacer>
      <!-- ----------------start menu1 -->
     <v-menu open-on-hover bottom offset-y class="z-100" max-width="150px">
      <template v-slot:activator="{ on, attrs }">
        <v-hover v-slot="{ hover }">
          <v-btn dark text v-bind="attrs" v-on="on" class="ma-0 smal px-1 caption" :color="hover ? '#009688' : 'grey darken-2'" >
            <v-icon :color="hover ? '#009688' : 'grey darken-2'" small>mdi-account</v-icon> My Account <v-icon :color="hover ? '#009688' : 'grey darken-2'" small>mdi-chevron-down</v-icon>
          </v-btn>
        </v-hover>
      </template>
      <div style="background-color:white">
          <v-btn text  width="100%" class="caption d-block abd justify-start pl-2"><v-icon small>mdi-account-arrow-left</v-icon> My Account</v-btn>
          <v-btn text  width="100%" class="caption d-block abd justify-start pl-2"><v-icon small>mdi-source-repository</v-icon> Order Repository</v-btn>
          <v-btn text  width="100%" class="caption d-block abd justify-start pl-2"><v-icon small>mdi-transit-connection-variant</v-icon> Transactions</v-btn>
          <v-btn text  width="100%" class="caption d-block abd justify-start pl-2"><v-icon small>mdi-download-box</v-icon> Downlouds</v-btn>
          <v-btn text  width="100%" class="caption d-block abd justify-start pl-2"><v-icon small>mdi-logout</v-icon> LogOut</v-btn>
          </div>
    </v-menu>
     <!--------------------------end menu1 -->
      <!-- ------------------start wish btn -->
      <v-hover v-slot="{ hover }">
        <v-btn class="px-2 smal caption"  :color="hover ? '#009688' : 'grey darken-2'"  text><v-icon :color="hover ? '#009688' : 'grey darken-2'" small>mdi-cards-heart</v-icon> Wish List (0)</v-btn>
      </v-hover>
      <!-- --------------------end wish btn -->
         
    </v-system-bar>
    <!-- ----------------------------------------------------------------------------end system bar -->
    <!-- ----------------------------------------------------------------------------start header part two -->
    <div>
      <header-2/>
    </div>
    <!-- ----------------------------------------------------------------------------end header part two -->
    <!-- ----------------------------------------------------------------------------start header part two -->
    <div>
     <header-3/>
    </div>
    <!-- ----------------------------------------------------------------------------end header part two -->
    
    
    
    <v-main>
      <router-view />
    </v-main>
    <!-- ----------------------------------------------------------------------------start footer-->
    <div>
    <thefooter/>
    </div>
    <!-- ----------------------------------------------------------------------------end footer -->
     
  </v-app>
</template>

<script>
import Thefooter from './components/footer/thefooter.vue';
import header2 from './components/header/header2.vue';
import Header3 from './components/header/header3.vue';
export default {
  components: { header2, Header3,Thefooter },
  name: "App",

  data: () => ({
  
  }),
};
</script>
<style scoped>
.abd:hover{
  color: #009688;
}
@media (max-width: 576px) { 
  .v-system-bar{
    display: flex;
    justify-content: center;
  }
  .spacer{
  display: none;
}
.v-application .caption{
  font-size:10px!important;
}

 }


</style>
