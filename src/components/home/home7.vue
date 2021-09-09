<template>
  <div class="home7 mb-15">
    <v-container>
      <v-row>
        <!-- ------------------- start part left -->
        <v-col cols="12" sm="4" md="3" class="pt-0">
          <v-card tile class="pb-0">
            <v-row class="ma-0">
              <v-col cols="6" sm="8" class="white--text clip pb-1 pr-0" style="background-color:#009688">
                TESTIMONIAL</v-col
              >
              <v-col
                cols="6"
                sm="4"
                style="border-bottom: 3px solid #009688; margin-left: -1.4px"
              >
              </v-col>
            </v-row>
<v-carousel :show-arrows="false" height="300" delimiter-icon="mdi-minus" cycle>
    <v-carousel-item
      reverse-transition="fade-transition"
      transition="fade-transition"
      class="pa-3 "
    >
    <p class="body-2">Lorem ipsum dolor sit amet consectetur ad  amet consectetur adipisicing elit. et consectetur ad  amet consectetur adipisicing elit. expedita repudiandae! Dolores iste aspernatur quibusdam?</p>
    <v-row class="ma-0 mt-6">
        <v-col cols="4 pa-0"><v-img src="@/assets/home/home7/qq.jpg"></v-img></v-col>
        <v-col cols="8 pt-5">
            <p class="mb-0" style="color:#009688">Michel Joe</p>
            <p class="grey--text mb-0 caption">Desginer</p>
        </v-col>
    </v-row>
    </v-carousel-item>
    <v-carousel-item
      reverse-transition="fade-transition"
      transition="fade-transition"
      class="pa-3 "
    >
    <p class="body-2">Lorem ipsum dolor sit amet consectetur ad  amet consectetur adipisicing elit. et consectetur ad  amet consectetur adipisicing elit. expedita repudiandae! Dolores iste aspernatur quibusdam?</p>
    <v-row class="ma-0 mt-6">
        <v-col cols="4 pa-0"><v-img src="@/assets/home/home7/qqq.jpg"></v-img></v-col>
        <v-col cols="8 pt-5">
            <p class=" mb-0" style="color:#009688">Mark Billy</p>
            <p class="grey--text mb-0 caption">Leader</p>
        </v-col>
    </v-row>
    </v-carousel-item>
    <v-carousel-item
      reverse-transition="fade-transition"
      transition="fade-transition"
      class="pa-3 "
    >
    <p class="body-2">Lorem ipsum dolor sit amet consectetur ad  amet consectetur adipisicing elit. et consectetur ad  amet consectetur adipisicing elit. expedita repudiandae! Dolores iste aspernatur quibusdam?</p>
    <v-row class="ma-0 mt-6">
        <v-col cols="4 pa-0"><v-img src="@/assets/home/home7/q.jpg"></v-img></v-col>
        <v-col cols="8 pt-5">
            <p class="mb-0" style="color:#009688">Jano FDH</p>
            <p class="grey--text mb-0 caption">Stylidt Maneger</p>
        </v-col>
    </v-row>
    </v-carousel-item>
    
  </v-carousel>

          </v-card>
        </v-col>
        <!-- ------------------- end part left -->
        <!-- ------------------------start part right -->
        <v-col cols="12" sm="8" md="9" class="pt-0 right-part">
          <v-row class="ma-0">
            <v-col cols="6" sm="4" lg="3" class="clip white--text" style="z-index:10;background-color:#009688">
              ELECTRONICS</v-col
            >
            <v-col cols="6" sm="8" lg="9" class="pa-0" >
                <div class="mobiles d-flex justify-end">
                    <v-btn-toggle class="ml-auto" style="height:94%">
                      <v-menu open-on-hover bottom offset-y class="z-100 d-flex d-sm-none" >
      <template v-slot:activator="{ on, attrs }">
          <v-btn dark text v-bind="attrs"  v-on="on" class="ma-0 d-flex d-sm-none" color="grey" icon>
            <v-icon>mdi-menu</v-icon>
          </v-btn>
      </template>
      <div style="background-color:white" class=" pa-2">
          <v-btn text class="d-block text-center caption my-1" width="100%" outlined>accssorite</v-btn >
          <v-btn text class="d-block text-center caption my-1" width="100%" outlined> Booke</v-btn >
          <v-btn text class="d-block text-center caption my-1" width="100%" outlined>Gift</v-btn >
          <v-btn text class="d-block text-center caption my-1" width="100%" outlined>screen</v-btn>
          </div>
    </v-menu>
          <v-btn text class="d-none d-sm-block" >
              accssorite
          </v-btn >
          <v-btn text class="d-none d-sm-flex">
              Booke
          </v-btn >
          <v-btn text class="d-none d-sm-flex">
              Gift
          </v-btn >
          <v-btn text class="d-none d-sm-flex">
              screen
          </v-btn>
        </v-btn-toggle>
                </div>
            </v-col>
          </v-row>
          <div class="imges">
              <v-img src="@/assets/home/home7/qqqq.png"></v-img>
          </div>
          <div class="items">
            <!-- .////////////////////slider items \\\\\\\\\\\\\\\\\\\\\ -->
           <vueper-slides
  class="no-shadow mt-5 father-slide"
  :visible-slides="4"
  :gap="2"
  autoplay
  :infinite="true"
  style="height:240px!important"
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
   <v-icon large color="#009688" dark>mdi-chevron-double-left</v-icon>
  </template>

  <template #arrow-right>
     <v-icon  large color="#009688" dark>mdi-chevron-double-right</v-icon>
  </template>
<!-- ////////////// left right icon \\\\\\\\\\\\\\\ -->


   <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
        color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrrrrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="3.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$342,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
       color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/rrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrrrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="3"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$221,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
       color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/rrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="3.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$334,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0"  class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile ><v-icon>mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home3/w.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home3/ww.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
       <v-rating
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          class="ml-3"
                          size="14"
                        ></v-rating>
        <p class="mb-0 font-weight-bold ml-4" style="color:#009688">$431,00</p>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
       color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/ww.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/w.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="2.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$321,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
        color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home3/ww.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="4.8"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$345,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
       color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$122,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
 
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
        color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/w.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home3/ww.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$234,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
        color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$223,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
       color="red accent-4"
      overlap
      bordered
      dot
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home3/ww.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home3/w.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="3"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$431,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card  elevation="0" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      bordered
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          :value="2.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
        <span class="ml-2 font-weight-bold" style="color:#009688">$234,00</span>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  

</vueper-slides>
<!-- -////////////////////// end slider items \\\\\\\\\\\\\\\\ -->
          </div>
        </v-col>
        <!-- ------------------------end part right -->
      </v-row>
    </v-container>
  </div>
</template>
<script>
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'
export default {
  name: "home7",
  data() {
    return {
      onboarding: 0,
      length: 5,
      slides: [
    {
      title: 'Slide #1',
      content: 'Slide content.'
    }
  ]
    }
  },
  components: { VueperSlides, VueperSlide },
};
</script>
<style >
.clip {
  clip-path: polygon(0 0, 84% 0, 100% 100%, 0% 100%);
  border: 0!important;
}
@media (min-width: 600px) and (max-width: 800px) {
  .home7 .item .row .col {
    padding-left: 0px;
    padding-right: 0px;
    padding-bottom: 10px;
  }
  .home7 .v-rating .v-icon {
    font-size: 12px !important;
  }
}
.mobiles{
    border-top: 2px solid rgb(185, 185, 185);
    border-right: 2px solid rgb(185, 185, 185);
    width: 110%;
    margin-left: -10%;
    z-index: -1;
    height: 90%;
    margin-bottom: -16px;
    margin-top: 6px;
    overflow: hidden;
}
.home7 .mobiles .v-btn{
    border: none!important;
    border-left: 1px solid grey!important;
    height: 100%;
}
.home7 .mobiles .v-item-group{
    margin-bottom: 1px;
}
.v-btn-toggle:not(.v-btn-toggle--dense) .v-btn.v-btn.v-size--default{
    height: 100%!important;
}

.vueperslides__parallax-wrapper,.vueperslides__inner{
  height: 100%;
}
.vueperslides__arrows--outside .vueperslides__arrow--prev {
    left: -0.5em;
}
.vueperslides__arrows--outside .vueperslides__arrow--next {
    right: -0.5em;
}
.home7 .v-card{
  overflow: hidden;
}
.home7 .outer{
  position: absolute;
  top: 23%;
  right: -105px;
  z-index: 10;
  transition: all .5s linear;
}
.home7 .outer .v-btn:hover{
  background-color: #D50000!important;
}
.home7 .outer .v-btn{
  transition: all .3s linear;
   border-radius: 7px;
}
.home7 .v-card:hover .outer{
  right: 5px;
}
.home7 .v-card:hover .sec{
  transform: rotateY(360deg);
}
.home7 .v-card:hover .fst{
  transform: rotateY(180deg);
}
.v-btn:not(.v-btn--round).v-size--default{
min-width: 30px;
height: 30px;
}
.home7 .v-card .sec{
  position: absolute;
  top: 0px;
  transform: rotateY(180deg);
  backface-visibility: hidden;
    transition: all .5s linear;
}
.home7 .v-card .fst{
  position: absolute;
    backface-visibility: hidden;
  top: 0px;
    transition: all .5s linear;
}
.home7 .v-card:hover .the-btn{
  color: #D50000!important;
  transition: all .2s linear;
}
@media (max-width: 576px) { 
  .home7 .v-badge .v-avatar{
    width: 110px!important;
  }
  .home7 .v-badge .v-image__image--cover{
    background-position:right center!important
  }

 }
 .home7 .father-slide{
   border: 2px solid rgb(202, 202, 202);
 }
 .v-rating{
   margin-top: -10px;
 }
  @media (max-width: 1200px) { 
.home7 .v-btn-toggle .v-btn{
  font-size: 11px!important;
}
 }
@media home7(max-width: 880px) { 
  .home7 .v-btn-toggle .v-btn{
  font-size: 10px!important;
  padding: 0 2px!important;
}
.home7 .clip.red{
  padding: 10px 5px;
  font-size: 12px!important;
}
 }
.home7 .v-image__image--cover{
  background-size: contain!important;
}
</style>
