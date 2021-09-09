<template>
  <div class="home2">
    <v-container>
      <v-row>
        <!-- ------------------- start part left -->
        <v-col cols="12" sm="4" md="3" class="pt-0">
          <v-card tile class="pb-4">
            <v-row class="ma-0">
              <v-col cols="6" sm="8" style="background-color:#009688" class=" white--text clip pb-0 pr-0">
                CATEGORIES</v-col
              >
              <v-col
                cols="6"
                sm="4"
                class="px-0 text-center py-1"
                style="border-bottom: 3px solid #009688; margin-left: -3px"
              >
                <v-btn text width="20px" tile @click="prev()" icon>
                  <v-icon>mdi-chevron-left</v-icon>
                </v-btn>
                <v-btn text width="20px" tile @click="next()" icon>
                  <v-icon>mdi-chevron-right</v-icon>
                </v-btn>
              </v-col>
            </v-row>
            <v-window v-model="onboarding" reverse class="pa-2" >
              <v-window-item>
                <div class="item">
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzzzzzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">Josen gasten</p>
                        <v-rating
                          :value="3.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$98,99</p>
                      </div>
                    </v-col>
                  </v-row>
                  <v-divider inset class="mx-auto"></v-divider>
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzzzzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">Molaz open zase</p>
                        <v-rating
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$112,99</p>
                      </div>
                    </v-col>
                  </v-row>
                  <v-divider inset class="mx-auto"></v-divider>
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzzzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">Paze sima</p>
                        <v-rating
                          :value="5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$231,99</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-window-item>
              <v-window-item>
                <div class="item">
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">maset gasten</p>
                        <v-rating
                          :value="3.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$98,99</p>
                      </div>
                    </v-col>
                  </v-row>
                  <v-divider inset class="mx-auto"></v-divider>
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">Molaz zase</p>
                        <v-rating
                          :value="4.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$112,99</p>
                      </div>
                    </v-col>
                  </v-row>
                  <v-divider inset class="mx-auto"></v-divider>
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzzzzzzzzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">Paze kite</p>
                        <v-rating
                          :value="2"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$75,99</p>
                      </div>
                    </v-col>
                  </v-row>
                </div> </v-window-item
              ><v-window-item>
                <div class="item">
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/z.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">maset gasten</p>
                        <v-rating
                          :value="1.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$55,99</p>
                      </div>
                    </v-col>
                  </v-row>
                  <v-divider inset class="mx-auto"></v-divider>
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">tren zase</p>
                        <v-rating
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$212,99</p>
                      </div>
                    </v-col>
                  </v-row>
                  <v-divider inset class="mx-auto"></v-divider>
                  <v-row>
                    <v-col cols="5">
                      <v-img
                        src="@/assets/home/home2/zzzzzzzz.jpg"
                        class="my-2"
                      ></v-img>
                    </v-col>
                    <v-col cols="7" class="d-flex align-center">
                      <div class="inner">
                        <p class="mb-0 caption">Paze sima</p>
                        <v-rating
                          :value="5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        <p class="red--text mb-0">$321,99</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-window-item>
            </v-window>
          </v-card>
        </v-col>
        <!-- ------------------- end part left -->
        <!-- ------------------------start part right -->
        <v-col cols="12" sm="8" md="9" class="pt-0 right-part">
          <v-row class="ma-0 mb-4">
            <v-col cols="6" sm="4" lg="3" class="clip white--text" style="background-color:#009688">
              HOT DEALS</v-col
            >
            <v-col cols="6" sm="8" lg="9" ></v-col>
          </v-row>
          <div class="items">
            <!-- .////////////////////slider items \\\\\\\\\\\\\\\\\\\\\ -->
           <vueper-slides
  class="no-shadow"
  :visible-slides="4"
  :gap="2"
  autoplay
  :infinite="true"
  style="height:280px!important"
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
   <v-icon large class="grey" dark>mdi-chevron-double-left</v-icon>
  </template>

  <template #arrow-right>
     <v-icon  large class="grey" dark>mdi-chevron-double-right</v-icon>
  </template>
<!-- ////////////// left right icon \\\\\\\\\\\\\\\ -->


  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile ><v-icon>mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/z.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-9%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">mosan</p>
        <span class="text-decoration-line-through caption">$555,00</span>
        <span class="ml-2 red--text font-weight-bold">$431,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-31%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">ko mosan</p>
        <span class="text-decoration-line-through caption">$321,00</span>
        <span class="ml-2 red--text font-weight-bold">$221,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-11%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">koran</p>
        <span class="text-decoration-line-through caption">$443,00</span>
        <span class="ml-2 red--text font-weight-bold">$334,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/z.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-25%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">kore misan</p>
        <span class="text-decoration-line-through caption">$434,00</span>
        <span class="ml-2 red--text font-weight-bold">$321,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-14%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">koire mosan</p>
        <span class="text-decoration-line-through caption">$453,00</span>
        <span class="ml-2 red--text font-weight-bold">$345,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-22%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">kore man</p>
        <span class="text-decoration-line-through caption">$222,00</span>
        <span class="ml-2 red--text font-weight-bold">$122,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-42%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">kore mosan</p>
        <span class="text-decoration-line-through caption">$555,00</span>
        <span class="ml-2 red--text font-weight-bold">$342,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-17%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">kore mire </p>
        <span class="text-decoration-line-through caption">$443,00</span>
        <span class="ml-2 red--text font-weight-bold">$234,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-21%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1"> mire mosan</p>
        <span class="text-decoration-line-through caption">$332,00</span>
        <span class="ml-2 red--text font-weight-bold">$223,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-19%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">korire mosan</p>
        <span class="text-decoration-line-through caption">$634,00</span>
        <span class="ml-2 red--text font-weight-bold">$431,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
    </v-card>
    </template>
  </vueper-slide>
  <!-- -------------------------end item -->
  <!-- -------------------------start item -->
  <vueper-slide class="the-slide">
    <template #content>
    <v-card outlined elevation="2" class="pa-4 " style="position:relative">
      <div class="outer">
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-2 my-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="grey accent-4"
      overlap
      offset-y="40"
      offset-x="40"
    >
    <v-avatar size="150" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       <template v-slot:badge>
         <p class="font-weight-bold">-19%</p>
        </template>
       </v-badge>
       </div>
        <p class="mb-1 body-1">kore mir</p>
        <span class="text-decoration-line-through caption">$345,00</span>
        <span class="ml-2 red--text font-weight-bold">$234,00</span>
        <v-btn text width="100%" class="mt-2 the-btn" outlined color="grey">buy <v-icon>mdi-shopping</v-icon></v-btn>
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
  name: "home2",
  data() {
    return {
      onboarding: 0,
      length: 3,
      content:"aaaaaaaaaaaaaaa",
    slides: [
    {
      title: 'Slide #1',
      content: 'Slide content.'
    }
  ]
    }
  },
  components: { VueperSlides, VueperSlide },
  methods: {
    next() {
      this.onboarding =
        this.onboarding + 1 === this.length ? 0 : this.onboarding + 1;
    },
    prev() {
      this.onboarding =
        this.onboarding - 1 < 0 ? this.length - 1 : this.onboarding - 1;
    },
  },
};
</script>
<style >
.clip {
  clip-path: polygon(0 0, 84% 0, 100% 100%, 0% 100%);
  border: 0!important;
}
@media (min-width: 600px) and (max-width: 800px) {
  .home2 .item .row .col {
    padding-left: 0px;
    padding-right: 0px;
    padding-bottom: 10px;
  }
  .home2 .v-rating .v-icon {
    font-size: 12px !important;
  }
}
.right-part .row > div {
  border-bottom: 3px solid #009688;
}
.right-part .row > div:last-of-type {
  margin-left: -1px;
}
.home2 .v-badge__badge{
  height: 37px!important;
  width: 37px!important;
  border-radius: 10px;
  padding-top: 13px;
  border: 1px solid white;
  text-align: center;
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

.home2 .outer{
  position: absolute;
  top: -120%;
  right: 5px;
  z-index: 10;
  transition: all .5s linear;
}
.home2 .outer .v-btn:hover{
  background-color: #009688!important;
}
.home2 .outer .v-btn{
  transition: all .3s linear;
   border-radius: 7px;
}
.home2 .v-card:hover .outer{
  top: 21%;
}
.home2 .v-card:hover .sec{
  top: 0;
}
.home2 .v-card:hover .fst{
  top: 300px;
}
.v-btn:not(.v-btn--round).v-size--default{
min-width: 30px;
height: 30px;
}
.home2 .v-card .sec{
  position: absolute;
  top: -300px;
    transition: all .5s linear;
}
.home2 .v-card .fst{
  position: absolute;
  top: 0px;
    transition: all .5s linear;
}
.home2 .v-card:hover .the-btn{
  color: #009688!important;
  transition: all .2s linear;
}
.home2 .v-card:hover .v-badge__badge.grey{
  background-color: #009688!important;
  transition: all .2s linear;
}
@media (max-width: 576px) { 
  .home2 .v-badge .v-avatar{
    width: 110px!important;
  }
  .home2 .v-badge .v-image__image--cover{
    background-position:right center!important
  }
 }
 .home2 .v-window{
   height: 350px;
 }
 @media (min-width: 960px ) and (max-width:1265px ) {
    .home2 .v-window{
   height: 250px!important;
 }
}
@media (max-width: 600px) { 
  .home2 .v-window{
   height: unset!important;
 }
 }
 .home2 .v-image__image--cover{
  background-size: contain!important;
}
</style>
