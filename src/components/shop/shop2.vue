<template>
    <div class="shop2 my-10">
        <v-container>
            <h1>SHOP</h1>
          <div class="bar">
              <v-row>
                  <v-col class="text-left">
                       <v-menu bottom offset-y max-width="220px" open-on-hover>
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="grey darken-3"
          small
          outlined
          v-bind="attrs"
          text
          v-on="on"
        >
          Sort By Price :low to high
        </v-btn>
      </template>
        <div class="white py-2">
            <v-btn small width="100%"  class="caption justify-start" text color="black">Sort By Price :high to low</v-btn>
            <v-btn small width="100%" class="caption justify-start" text color="black">Sort By Price :low to high</v-btn>
            <v-btn small width="100%" class="caption justify-start" text color="black">Sort By popularity</v-btn>
            <v-btn small width="100%" class="caption justify-start" text color="black">Sort By Avarge Rating</v-btn>
            <v-btn small width="100%" class="caption justify-start" text color="black">Sort By Latest</v-btn>
        </div>
    </v-menu>
                  </v-col>
                  <v-col class="text-right">
                       <v-menu bottom offset-y max-width="120px" class="ml-auto" open-on-hover max-height="200px">
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="grey darken-3"
          small
          outlined
          v-bind="attrs"
          text
          v-on="on"
        >
          32 <v-icon>mdi-chevron-down</v-icon>
        </v-btn>
      </template>
        <div class="white py-2" >
            <v-btn small width="100%"  class="caption justify-start" text color="grey">1</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">2</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">3</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">4</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">5</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">6</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">7</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">8</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">9</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">10</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">11</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">12</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">13</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">14</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">15</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">16</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">17</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">18</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">19</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">20</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">21</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">22</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">23</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">24</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">25</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">26</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">27</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">28</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">29</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">30</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">31</v-btn>
            <v-btn small width="100%"  class="caption justify-start" text color="grey">32</v-btn>
        </div>
    </v-menu>
                  </v-col>
              </v-row>
        </div>

     <!---------------------------------------------------------------- start items -->
       <v-row class="ma-0 mt-3">
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Drumstick tenderloin</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$12.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rr.png"  class="fst" ></v-img>
      <v-img src="@/assets/shop/v.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="1"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Landjaeger shankle</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$25.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrrrrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Kiza sima poka</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$34.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="3"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Capicola sausagops</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$11.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rrrrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrr.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="2"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Xaze miza duma</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$51.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/z.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="4"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Zase mate ruka</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$8.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/zzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="1"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Gaze sase tika</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$41.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="3"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Chicken kielbasa</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$22.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Hamburger shoulder</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$13.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="1"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Meatball brisketings</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$18.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzzzzzzzzzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="3"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Shoulder hamburger</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$21.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/zzzzzzzzzzzzzz.jpg"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/ww.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="2"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Paze sima kite</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$25.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/ww.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/www.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="3.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Turducken cillum</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$11.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/wwwwwww.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/zzzz.jpg"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="1.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Piza sima poza</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$34.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/www.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/wwwww.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="4.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Miza sima poza lira</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$17.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
         <v-col cols="6" sm="4" md="3">
            <v-card  elevation="0" width="100%" outlined style="position:relative;cursor:pointer" class="pa-3">
      <div class="outer-icon">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon >mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="180" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/w.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/wwww.png"  class="sec" ></v-img>
       </v-avatar>
       </v-badge>
       </div>
        <v-rating
                          class="ml-2"
                          :value="3"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="19"
                        ></v-rating>
        <p class="ml-2 mb-1 name-item">Esami tera sima</p>
        <p class="ml-2 text-h5 font-weight-bold red--text">$32.00</p>
        <v-btn text width="100%" class="caption" color="#009688" outlined>BUY NOW <v-icon right>mdi-shopping</v-icon></v-btn>
    </v-card>
         </v-col>
       </v-row>
        <!---------------------------------------------------------------- end items -->

<div class="bar mt-15 py-1 grey lighten-5">
  <v-pagination
              v-model="page"
              class="my-4"
              :length="5"
              color="#009688"
              prev-icon="mdi-menu-left"
      next-icon="mdi-menu-right"
            ></v-pagination>
</div>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"shop2",
     data () {
      return {
        page: 1,
      }
    },
}
</script>
<style >
.shop2 .bar{
    border: 1px solid rgb(170, 170, 170);
    padding: 10px;
}
 .shop2 .outer-icon{
  position: absolute;
  top: 23%;
  right: -105px;
  z-index: 10;
  transition: all .5s linear;
}
.shop2 .outer-icon .v-btn:hover{
  background-color: #009688!important;
}
.shop2 .outer-icon .v-btn{
  transition: all .3s linear;
   border-radius: 10px;
}
.shop2 .v-card:hover .outer-icon{
  right: 5px;
}
.shop2 .v-card:hover .sec{
  transform: rotateY(360deg);
}
.shop2 .v-card:hover .fst{
  transform: rotateY(180deg);
}
.shop2 .v-card .sec{
  position: absolute;
  top: 0px;
  transform: rotateY(180deg);
  backface-visibility: hidden;
    transition: all .5s linear;
}
.shop2 .v-card .fst{
  position: absolute;
    backface-visibility: hidden;
  top: 0px;
    transition: all .5s linear;
}
 .v-card:hover p.name-item{
  color: #009688!important;
  transition: all .2s linear;
}
 .v-card:hover .v-badge__badge{
  background-color: #009688!important;
  transition: all .2s linear;
}
.shop2 .v-card:hover{
  box-shadow: 0px 3px 3px -2px rgb(0 0 0 / 20%), 0px 3px 4px 0px rgb(0 0 0 / 14%), 0px 1px 8px 0px rgb(0 0 0 / 12%) !important;
transition: all .2s linear;
}
@media (max-width: 576px) { 
.shop2 .v-badge{
  width: 140px;
  height: 140px;
}
.shop2 .v-avatar{
  height: 120px!important;
    min-width: 120px!important;
    width: 120px!important;
}
}
</style>