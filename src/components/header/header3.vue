<template>
    <div class="header3">
      <v-container style="height:100%" class="py-0">
       <v-row style="height:100%" class="mt-0">
           <v-col cols="7" sm="9" md="10" class="py-0 btns">
               <v-btn router to="/" style="height:100%" tile color="white" text class="caption d-none d-md-inline-flex">Home</v-btn>
               <!-- ------------------------------start menu1 -->
<v-menu
    offset-y
      bottom
      open-on-hover
      transition="scale-transition"
    >
      <template v-slot:activator="{ on, attrs }">
<v-btn style="height:100%" v-on="on"  v-bind="attrs" tile color="white" text  class="caption d-none d-md-inline-flex">MOBILES <v-icon small right>mdi-chevron-down</v-icon></v-btn>
      </template>
    <div class="white pa-5 py-6 " style="width:550px; height:275px;">
        <v-row>
            <v-col cols="4">
                <p class="fst-text">ACCESSORIES</p>
                <v-btn width="100%" plain class="abd justify-start px-0">Screen Protectore</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Other Accessories</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Momary Card</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Chargers</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Cases & Cover</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Security Software</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Bluetooth</v-btn>
            </v-col>
            <v-col cols="4" style="border-left:1px solid #DDD;border-right:1px solid #DDD">
                <p class="fst-text">MOBILES BRANDS</p>
                <v-btn width="100%" plain class="abd justify-start px-0">Samsung</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Sony</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Nokia</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Micromax</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">LG</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">HTC</v-btn>
                <v-btn width="100%" plain class="abd justify-start px-0">Apple</v-btn>
            </v-col>
            <v-col cols="4">
                <v-img src="@/assets/header/abd.png" class="mt-5"></v-img>
            </v-col>
        </v-row>
    </div>
    </v-menu>
<!-- ------------------------------ end menu1 -->
 <!-- ------------------------------start menu2 -->
<v-menu
    offset-y
      bottom
      open-on-hover
      transition="scale-transition"
    >
      <template v-slot:activator="{ on, attrs }">
 <v-btn style="height:100%" v-on="on"  v-bind="attrs" tile color="white" text  class="caption d-none d-md-inline-flex">ELECTRONICE  <v-icon right small>mdi-chevron-down</v-icon></v-btn>
      </template>
      <div  style="width:700px;height:240px" class="pa-0">
        <v-row class="ma-0 pa-0" style="height:100%">
            <v-col cols="3" class="grey lighten-3 pt-1 px-0"> 
                <p style="background-color:#009688" class="white--text pa-2 mb-1 text-center">CATEGORIES <v-icon color="white" class=" ml-auto">mdi-menu-down</v-icon></p>
                <v-btn text width="100%" class="px-2 justify-start">Aperal <v-icon class="ml-auto">mdi-menu-right</v-icon></v-btn>
                <v-btn text width="100%" class="px-2 justify-start">Football <v-icon class="ml-auto">mdi-menu-right</v-icon></v-btn>
                <v-btn text width="100%" class="px-2 justify-start">Footwear <v-icon class="ml-auto">mdi-menu-right</v-icon></v-btn>
                <v-btn text width="100%" class="px-2 justify-start">Veiteball <v-icon class="ml-auto">mdi-menu-right</v-icon></v-btn>
                <v-btn text width="100%" class="px-2 justify-start">Consectetur <v-icon class="ml-auto">mdi-menu-right</v-icon></v-btn>
            </v-col>
            <v-col cols="9" class="white py-4"> 
<!-- -----------------------start cart items -->
 <v-card  elevation="0" width="150px" height="200px" outlined style="position:relative;cursor:pointer" class="mx-2 d-inline-block">
      <div class="cart-outer">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      bordered
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="110" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rrrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrr.png"  class="sec" ></v-img>
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
        <span class="ml-2 font-weight-bold">item-1</span>
    </v-card>
    <v-card  elevation="0" width="150px" height="200px" outlined style="position:relative;cursor:pointer" class="mr-2 d-inline-block">
      <div class="cart-outer">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      bordered
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="110" class="mb-7" style="position:relative">
      <v-img src="@/assets/home/home2/rrr.png"  class="fst" ></v-img>
      <v-img src="@/assets/home/home2/rrrrrrrrrr.png"  class="sec" ></v-img>
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
        <span class="ml-2 font-weight-bold">item-2</span>
    </v-card>
    <v-card  elevation="0" width="150px" height="200px" outlined style="position:relative;cursor:pointer" class="d-inline-block">
      <div class="cart-outer">
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-cards-heart</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-shopping-outline</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-arrow-all</v-icon></v-btn><br/>
        <v-btn depressed  class="pa-0 grey darken-1 mb-1" dark tile><v-icon small>mdi-search-web</v-icon></v-btn><br/>
      </div>
          <div class="d-flex justify-center">
         <v-badge
      color="red accent-4"
      overlap
      dot
      bordered
      offset-y="30"
      offset-x="30"
    >
    <v-avatar size="110" class="mb-7" style="position:relative">
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
        <span class="ml-2 font-weight-bold">item-3</span>
    </v-card>
<!-- -----------------------end cart items -->
            </v-col>
        </v-row>
        </div>
    </v-menu>
<!-- ------------------------------end menu2 -->
               <v-btn router to="/about" style="height:100%" tile color="white" text  class="caption d-none d-md-inline-flex">About Us</v-btn>
              <v-badge
        bordered
        color="green"
       content="new!"
        offset-x="50"
        style="height:100%!important"
        offset-y="4"
        tile
      >
               <v-btn style="height:100%" tile to="/shop" router color="white" text  class="caption d-none d-md-inline-flex">SHOP</v-btn>
                    </v-badge>
               <v-btn style="height:100%" to="/contact" router tile color="white" text  class="caption d-none d-md-inline-flex">Contact Us</v-btn>
               <!-- button to open the nevigation drawer  -->
               <v-btn style="height:100%;margin-top:-30px" tile color="white" text  class="d-md-none" @click="drawer=!drawer"><v-icon>mdi-menu</v-icon></v-btn>
<!-- ---------- //////////////////////////////////////////// navigation drwer -->
<v-navigation-drawer
      v-model="drawer"
      app
      left
      temporary
      width="300px"
    >
    <div class="outer ma-0" >
        <v-row class="pa-2 pt-1">
            <v-col cols="9 pl-5 pb-2" ><v-icon small color="black">mdi-phone-classic</v-icon> <span class="caption">(801)2345-876</span></v-col>
            <v-col cols="3"><v-btn tile height="100%" width="100%" @click="drawer =false" text><v-icon >mdi-close</v-icon></v-btn></v-col>
        </v-row>
    </div>
    <div class="first-items grey lighten-4">
        <v-text-field
              dense
              color="grey"
            outlined
            label="Search item.."
            append-icon="mdi-search-web"
            class="ma-3 mt-0 pt-1"
          ></v-text-field>
          <v-btn-toggle
          mandatory
          class="grey lighten-4"
          active-class="active"
          style="height:50px;width:100%"
        >
            <v-btn elevation="0" @click="showmenu()"  outlined text tile  width="50%" class="text-left d-block"><v-icon>mdi-notification-clear-all</v-icon> MENU</v-btn>
              <v-btn  elevation="0"  @click="showcategory()" outlined width="50%" text tile class="text-left px-0 pl-1 d-block"><v-icon>mdi-collage</v-icon> CATEGORIES</v-btn>
          </v-btn-toggle>
    </div>
    <div class="menu-item mt-3" v-if="menu">
        <v-btn elevation="0" router to="/" class="text-left" color="black" plain dark height="47px" tile width="94%">Home <v-icon style="margin-left:70%">mdi-chevron-right</v-icon></v-btn>
        <v-btn elevation="0" router to="/about" class="text-left" color="black" plain dark height="47px" tile width="94%">About Us <v-icon style="margin-left:59%">mdi-chevron-right</v-icon></v-btn>
        <v-btn elevation="0" router to="/shop" class="text-left" color="black" plain dark height="47px" tile width="94%">SHOP <v-icon style="margin-left:64%">mdi-chevron-right</v-icon></v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">ELECTRONICE<v-icon style="margin-left:47%">mdi-chevron-right</v-icon></v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">BLOG <v-icon style="margin-left:72%">mdi-chevron-right</v-icon></v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">PAGES <v-icon style="margin-left:69%">mdi-chevron-right</v-icon></v-btn>
        <v-btn elevation="0" router to="/contact" class="text-left" color="black" plain dark height="47px" tile width="94%">CONTACT US <v-icon style="margin-left:49%">mdi-chevron-right</v-icon></v-btn>
    </div>
    <div class="menu-item mt-3" v-if="category">
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">ELECTRONICE</v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">BOOK & MAGAZEN </v-btn>
         <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">GIFT</v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">SPORT & FITNESS</v-btn>
         <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">COMPUTER & LAPTOP</v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">MOVE & MUSIC</v-btn>
          <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">FOOD & DRINK</v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">BUETY & HEALTHY</v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">KITCHEN</v-btn>
        <v-btn elevation="0" class="text-left" color="black" plain dark height="47px" tile width="94%">BABY CARE & TOYS</v-btn>
    </div>

    </v-navigation-drawer>
<!-- -------------------------------------- ///////////////////////////// end navigation drwer -->
           </v-col>
           <v-col cols="5" sm="3" md="2" class="py-0 cart">
              
              <!-- start disloge -->
               <v-dialog
      v-model="dialog"
      persistent
      max-width="320"
      scrollable
    >
      <template v-slot:activator="{ on, attrs }">
         <v-btn v-bind="attrs" v-on="on" style="height:100%"  depressed width="100%" tile color="#009688"  dark><v-icon small>mdi-shopping</v-icon> MY CART <v-btn tile class="px-0 ml-2 small-btn" color="#009688">6</v-btn></v-btn>
      </template>
      <v-card>
        <v-card-title style="border-bottom:1px solid #009688">Your Items:</v-card-title>
      <v-card-text style="height: 300px;" class="px-2">
        <v-card outlined class="pa-0 my-2 ">
          <v-row class="ma-0">
            <v-col cols="3" class="pa-1">
              <v-img src="@/assets/home/home2/rrrrr.png" style="border:1px solid #EEE"></v-img>
            </v-col>
            <v-col cols="5" class="d-flex align-center pa-1">
              <div>
                <p class="mb-0 caption">desctop computer.</p>
              <p class="mb-0 caption">WE12A</p>
              </div>
            </v-col>
            <v-col cols="2" class="caption pa-0 d-flex align-center pa-1" style="color:#009688!important">
              $1200,0
            </v-col>
            <v-col cols="2" class="caption pa-0 red--text d-flex align-center justify-center pa-1">
              <v-btn icon class="pa-0" color="red"><v-icon >mdi-delete</v-icon></v-btn>
            </v-col>
          </v-row>
        </v-card>
        <v-card outlined class="pa-0 my-2 ">
          <v-row class="ma-0">
            <v-col cols="3" class="pa-1">
              <v-img src="@/assets/home/home2/rr.png" style="border:1px solid #EEE"></v-img>
            </v-col>
            <v-col cols="5" class="d-flex align-center pa-1">
              <div>
                <p class="mb-0 caption">mokis shoes.</p>
              <p class="mb-0 caption">QAS6</p>
              </div>
            </v-col>
            <v-col cols="2" class="caption pa-0 d-flex align-center pa-1" style="color:#009688!important">
              $1000,0
            </v-col>
            <v-col cols="2" class="caption pa-0 red--text d-flex align-center justify-center pa-1">
              <v-btn icon class="pa-0" color="red"><v-icon >mdi-delete</v-icon></v-btn>
            </v-col>
          </v-row>
        </v-card>
        <v-card outlined class="pa-0 my-2 ">
          <v-row class="ma-0">
            <v-col cols="3" class="pa-1">
              <v-img src="@/assets/home/home2/rrrrrr.png" style="border:1px solid #EEE"></v-img>
            </v-col>
            <v-col cols="5" class="d-flex align-center pa-1">
              <div>
                <p class="mb-0 caption">france jolary.</p>
              <p class="mb-0 caption">SSA32</p>
              </div>
            </v-col>
            <v-col cols="2" class="caption pa-0 d-flex align-center pa-1" style="color:#009688!important">
              $3200,0
            </v-col>
            <v-col cols="2" class="caption pa-0 red--text d-flex align-center justify-center pa-1">
              <v-btn icon class="pa-0" color="red"><v-icon >mdi-delete</v-icon></v-btn>
            </v-col>
          </v-row>
        </v-card>
        <v-card outlined class="pa-0 my-2 ">
          <v-row class="ma-0">
            <v-col cols="3" class="pa-1">
              <v-img src="@/assets/home/home2/rrr.png" style="border:1px solid #EEE"></v-img>
            </v-col>
            <v-col cols="5" class="d-flex align-center pa-1">
              <div>
                <p class="mb-0 caption">horor camera.</p>
              <p class="mb-0 caption">AAZ22</p>
              </div>
            </v-col>
            <v-col cols="2" class="caption pa-0 d-flex align-center pa-1" style="color:#009688!important">
              $1900,0
            </v-col>
            <v-col cols="2" class="caption pa-0 red--text d-flex align-center justify-center pa-1">
              <v-btn icon class="pa-0" color="red"><v-icon >mdi-delete</v-icon></v-btn>
            </v-col>
          </v-row>
        </v-card>
        <v-card outlined class="pa-0 my-2 ">
          <v-row class="ma-0">
            <v-col cols="3" class="pa-1">
              <v-img src="@/assets/home/home2/rrrrrrrr.png" style="border:1px solid #EEE"></v-img>
            </v-col>
            <v-col cols="5" class="d-flex align-center pa-1">
              <div>
                <p class="mb-0 caption">apple ipad.</p>
              <p class="mb-0 caption">AAP9</p>
              </div>
            </v-col>
            <v-col cols="2" class="caption pa-0 d-flex align-center pa-1" style="color:#009688!important">
              $3300,0
            </v-col>
            <v-col cols="2" class="caption pa-0 red--text d-flex align-center justify-center pa-1">
              <v-btn icon class="pa-0" color="red"><v-icon >mdi-delete</v-icon></v-btn>
            </v-col>
          </v-row>
        </v-card>
        <v-card outlined class="pa-0 my-2 ">
          <v-row class="ma-0">
            <v-col cols="3" class="pa-1">
              <v-img src="@/assets/home/home2/zzz.jpg" style="border:1px solid #EEE"></v-img>
            </v-col>
            <v-col cols="5" class="d-flex align-center pa-1">
              <div>
                <p class="mb-0 caption">Caps.</p>
              <p class="mb-0 caption">CA99</p>
              </div>
            </v-col>
            <v-col cols="2" class="caption pa-0 d-flex align-center pa-1" style="color:#009688!important">
              $500,0
            </v-col>
            <v-col cols="2" class="caption pa-0 red--text d-flex align-center justify-center pa-1">
              <v-btn icon class="pa-0" color="red"><v-icon >mdi-delete</v-icon></v-btn>
            </v-col>
          </v-row>
        </v-card>
      </v-card-text>
      <v-card-actions  style="border-top:1px solid #009688">
          
          <v-btn
            color="#009688"
            outlined
            @click="dialog = false"
          >
            Buy All <v-icon right>mdi-shopping-outline</v-icon>
          </v-btn>
          <v-spacer></v-spacer>
          <v-btn
            color="#009688"
            outlined
            @click="dialog = false"
          >
            Cancel
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
              <!-- end disloge -->
           </v-col>
       </v-row>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"header3",
    data: () => ({
    drawer:false,
    menu:true,
    category:false,
     dialog: false,
  }),
  methods:{
      showmenu:function(){
          this.menu=true;
          this.category=false;
      },
      showcategory:function(){
          this.menu=false;
          this.category=true;
      }
  }
}
</script>
<style >
.header3{
    background-color: #2c2c2c;
    color: white;
    height: 40px;
}
.fst-text{
    font-weight: bold;
    font-size: 15px;
    margin-bottom: 1px!important;
}
.abd{
    font-size: 11px!important;
}
.header3 .btns > .v-btn{
border-left: 1px solid grey;
border-right: 1px solid grey;
}
.header3 .small-btn {
min-width: 20px!important;
}
.header3 .cart{
    position: relative;
}
.header3 .cart::before{
    content: "";
    position: absolute;
    top: 0;
    left: -27px;
    width: 0px;
  height: 0px;
  border-style: solid;
  border-width: 20px;
  border-color: transparent #009688 transparent transparent; 
}
.header3 .outer-div2{
    width: 220px!important;
    height: 380px;
}
.header3 .v-btn__content{
    display: block!important;
}
.header3 .menu-item > .v-btn{
    border-bottom: 1px solid rgb(189, 189, 189);
    margin-left: 3%;
}
.header3 .menu-item > .v-btn:hover{
    color: #009688!important;
}
.header3 .v-btn-toggle .v-btn--active{
   background-color: white!important;
   color: #232123;
}
.header3 .outer{
    background-color: #f5f5f5;
    color: grey;
}
.header3 .outer .v-btn:hover{
    background-color: #009688;
    color: white;
}
.header3 .outer .v-btn{
   border-left: 1px solid grey;
}



.v-card{
  overflow: hidden;
}
 .cart-outer{
  position: absolute;
  top: 23%;
  right: -105px;
  z-index: 10;
  transition: all .5s linear;
}
.cart-outer .v-btn:hover{
  background-color: #009688!important;
}
.cart-outer .v-btn{
  transition: all .3s linear;
   border-radius: 50%;
}
 .v-card:hover .cart-outer{
  right: 5px;
}
.v-card:hover .sec{
  transform: rotateY(360deg);
}
 .v-card:hover .fst{
  transform: rotateY(180deg);
}
.v-btn:not(.v-btn--round).v-size--default{
min-width: 20px;
height: 20px;
}
 .v-card .sec{
  position: absolute;
  top: 0px;
  transform: rotateY(180deg);
  backface-visibility: hidden;
    transition: all .5s linear;
}
 .v-card .fst{
  position: absolute;
    backface-visibility: hidden;
  top: 0px;
    transition: all .5s linear;
}
 .v-card:hover .the-btn{
  color: #009688!important;
  transition: all .2s linear;
}
</style>