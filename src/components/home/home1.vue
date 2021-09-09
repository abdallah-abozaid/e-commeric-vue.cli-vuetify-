<template>
    <div class="home1">
        <v-container>
            <v-row>
                <!-- ------------------- start part left -->
                <v-col cols="12" sm="4" md="3"  order="2" order-sm="1"  class="pt-0">
                  <v-card tile class="pb-4">
                    <v-row class="white--text ma-0" style="background-color:#009688">
                      <v-col cols="2" style="background-color:#009688" class="px-0  text-center"> <v-icon dark>mdi-menu</v-icon></v-col>
                      <v-col cols="8"> CATEGORIES</v-col>
                      <v-col cols="2" class="px-0  text-center"> <v-icon dark>mdi-chevron-down</v-icon></v-col>
                    </v-row>
                    
                     <!-- ------------------------------ start menu2 in navigation -->
      <v-menu
    offset-x
      right
     max-width="350px"
     max-height="260px"
    open-on-hover
      transition="scale-transition"
    >
      <template v-slot:activator="{ on, attrs }">
       <v-btn text width="100%" v-on="on"  v-bind="attrs" class="body-2 mt-2 justify-start">TSHIRT <v-icon small class="ml-auto">mdi-chevron-down</v-icon></v-btn>
      </template>
    <div class="white pa-4 pt-5 mx-0">
        <v-row>
            <v-col cols="4" class="pa-0" style="border-right:1px solid #EEE">
               <v-btn text tile width="100%">mans</v-btn>
                <v-btn text tile width="100%">womans</v-btn>
                <v-btn text tile width="100%">kids</v-btn>
                <v-btn text tile width="100%">solid</v-btn>
                <v-btn text tile width="100%">print</v-btn>
                <v-btn text tile width="100%">fullseve</v-btn>
            </v-col>
            <v-col cols="8" >
    <v-img src="@/assets/home/home1/b.png"></v-img>
                <v-img  src="@/assets/home/home1/bb.png"></v-img>
            </v-col>
        </v-row>
    </div>
    </v-menu>
<!-- ------------------------------end menu2 in navigation -->
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">SMARTPHONE</v-btn>
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">ELECTRONIC</v-btn>
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">Furniture</v-btn>
                    <!-- ------------------------------ start menu2 in navigation -->
<v-menu
    offset-x
      right
     max-width="400px"
    open-on-hover
      transition="scale-transition"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn text width="100%" v-on="on"  v-bind="attrs" class="body-2  justify-start subtitle-1 mt-1">LABTOP & NOTBOOK <v-icon small class="ml-auto">mdi-chevron-down</v-icon></v-btn>
      </template>
    <div class="white pa-4 pt-5 mx-0">
        <v-row>
            <v-col cols="3" class="pa-0" style="border-right:1px solid #EEE">
                <v-btn text tile width="100%" disabled class="justify-start">LABTOP</v-btn>
                <v-btn plain  width="100%" small class="justify-start caption">APPLE</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">HTC</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">LG</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">MICROMAX</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">MOKIA</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">SAMSONGE</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">SONY</v-btn>
            </v-col>
            <v-col cols="3" class="pa-0" style="border-right:1px solid #EEE">
                <v-btn text tile  width="100%" disabled class="justify-start">NOTBOOK</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">womans</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">kids</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">solid</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">print</v-btn>
                <v-btn plain width="100%" small class="justify-start caption">fullseve</v-btn>
            </v-col>
            <v-col cols="6" >
              <v-card elevation="0" class="text-left">
    <v-img
      src="@/assets/home/home1/l.png"
      height="120px"
    ></v-img>
    <v-card-text>
        <v-rating
          :value="3.5"
          color="amber"
          dense
          half-increments
          readonly
          size="14"
        ></v-rating>

      <div class="caption">
       Molaz tren open zase
      </div>
      <div class="red--text body-1">
       $125,000
      </div>

    </v-card-text>
  </v-card>
            </v-col>
            
        </v-row>
    </div>
    </v-menu>
<!-- ------------------------------end menu2 in navigation -->
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">Houseware</v-btn>
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">COMPONENTS</v-btn>
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">Decorations</v-btn>
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">GIFT</v-btn>
                    <v-btn text width="100%" class="body-2  justify-start subtitle-1 mt-1">SPORT & FETNESS</v-btn>
                  </v-card>
                </v-col>
                <!-- ------------------- end part left -->
                <!-- ------------------------start part right -->
                <v-col cols="12" sm="8" md="9" order="1" order-sm="2"  class="pt-0">
                     <v-carousel cycle show-arrows-on-hover class="home-carsol" height="390px"  hide-delimiter-background delimiter-icon="mdi-window-minimize">
    <v-carousel-item
      src="@/assets/home/home1/w.jpg"
      reverse-transition="fade-transition"
      transition="fade-transition"
      
    >
    <div class="carosal">
    <div class="texts">
      <p class="mb-0 grey--text">Compare iPad models.</p>
    <h1>Houseware ProSuper.</h1>
    <h1>Now in two sizes.</h1>
    <p class="caption mb-0">Claritas est etiam processus dynamicus, qui sequitur mutationem consuetudium</p>
    <p class="caption"> lectorum. Mirum est notare quam littera gothica, quam nunc putamus parum </p>
    <v-btn color="#7E9488" tile dark small>Shop Now</v-btn>
    </div>
    </div>
    </v-carousel-item>
    <v-carousel-item
      src="@/assets/home/home1/ww.jpg"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
    <div class="carosal">
    <div class="texts">
      <p class="mb-0 grey--text">Compare iPad models.</p>
    <h1>Houseware ProSuper.</h1>
    <h1>Now in two sizes.</h1>
    <p class="caption mb-0">Claritas est etiam processus dynamicus, qui sequitur mutationem consuetudium</p>
    <p class="caption"> lectorum. Mirum est notare quam littera gothica, quam nunc putamus parum </p>
     <v-btn color="#C4D34F" tile dark small>Shop Now</v-btn>
    </div>
    </div>
    </v-carousel-item>
    <v-carousel-item
      src="@/assets/home/home1/www.jpg"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
    <div class="carosal">
    <div class="texts">
      <p class="mb-0 grey--text">Compare iPad models.</p>
    <h1>Houseware ProSuper.</h1>
    <h1>Now in two sizes.</h1>
    <p class="caption mb-0">Claritas est etiam processus dynamicus, qui sequitur mutationem consuetudium</p>
    <p class="caption"> lectorum. Mirum est notare quam littera gothica, quam nunc putamus parum </p>
     <v-btn color="#DF9F1B" tile dark small>Shop Now</v-btn>
    </div>
    </div>
    </v-carousel-item>
  </v-carousel>
                </v-col>
                <!-- ------------------------end part right -->
            </v-row>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"home1",
    data () {
      return {

      }
    },
}
</script>
<style scoped >
.theme--light.v-btn.v-btn--disabled{
  color: black!important;
}
.carosal p,.carosal h1{
  color: white!important;
  text-shadow: 2px 2px 4px rgb(37, 37, 37);
}
.carosal{
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.carosal .texts{
  width: 90%;
}
.v-btn.subtitle-1:hover{
  color: #009688;
}
.home1 .v-btn--icon.v-size--small .v-icon, .v-btn--fab.v-size--small .v-icon{
  color: #009688!important;
}
.home1 .v-btn--active{
  background-color: #009688;
}
@media (max-width: 960px) { 
.home1 .v-btn.subtitle-1{
font-size: 13px!important;
margin-top: 0px!important;
}

 }
 @media (max-width: 600px) { 
.home1 .home-carsol{
background-size: contain;
}

.home1 .v-image__image--cover{
background-position:left top!important;
}
 }
</style>