<template>
    <div class="about3">
        <v-container>
        <h2>OUR TEAMS</h2>
          <vueper-slides
  class="no-shadow"
  :visible-slides="4"
  :gap="2"
  autoplay
  :infinite="true"
   style="height:480px"
   :bullets="false"
  :slide-ratio="1 / 4"
  :dragging-distance="70"
  :breakpoints="{ 
    800: {
       visibleSlides: 2,
        slideMultiple: 1
         } ,
         1000:{
            visibleSlides: 3,
        slideMultiple: 1
         }
         
         }">

<!-- ////////////// left right icon \\\\\\\\\\\\\\\ -->
<template #arrow-left>
   <v-icon large class="grey rounded-xl" dark>mdi-chevron-left</v-icon>
  </template>

  <template #arrow-right>
     <v-icon  large class="grey rounded-xl" dark>mdi-chevron-right</v-icon>
  </template>
<!-- ////////////// left right icon \\\\\\\\\\\\\\\ -->


  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/d.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/dd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/ddd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/dddd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/ddddd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/dd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/d.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/ddd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/dddd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  class="pa-0 text-center" elevation="0" height="100%">
    <v-img
      height="250px"
      width="100%"
      src="@/assets/about/ddddd.jpg"
    ></v-img>

    <v-card-title class="justify-center py-2 pb-0">Cafe Badilico</v-card-title>
    <v-card-text class="caption py-2 text-center">Co Founder</v-card-text>
    <v-card-text class="caption py-0 text-center">Lorem ipsum dolor sit amet, Accusanti fugit  qua totam. Accusantium!</v-card-text>
    <a href="#"><v-icon large color="#39599F">mdi-facebook</v-icon></a>
    <a href="#"><v-icon large color="#45B0E3">mdi-twitter</v-icon></a>
    <a href="#"><v-icon large color="#1872BF">mdi-gmail</v-icon></a>
    <a href="#"><v-icon large color="#F8BC2E">mdi-linkedin</v-icon></a>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
 




 </vueper-slides>
 </v-container>
    </div>
</template>
<script>
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'
export default {
    name:"about3",
    components: { VueperSlides, VueperSlide },
}
</script>
<style scoped>
.about3 h2{
    width: 300px;
    text-align: center;
    margin: 20px auto 10px;
}
.about3 .v-card a{
    text-decoration: none;
}
</style>