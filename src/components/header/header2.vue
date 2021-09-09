<template>
    <div class="header2">
      <v-container>
       <v-row align="center" justify="center" class="ma-0" >
          <v-col cols="6" md="3" class="text-left display-1 font-weight-bold title-store" > 
              <v-badge
      color="#009688"
      overlap
      bordered
      dot
      offset-y="7"
      offset-x="1"
    >
            MAX<span style="color:#009688">SHOP</span>
              </v-badge>
          </v-col>
          <v-col cols="12" sm="8" md="6" class="d-none d-md-block">
             <v-row>
               <v-col cols="3 px-0">
                 <v-menu open-on-hover bottom max-width="200px" offset-y max-height="300px">
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          text
          class="categ px-0"
          v-bind="attrs"
          height="90%"
          tile
          dense
          v-on="on"
        >
          CATEGORY <v-icon right>mdi-chevron-down</v-icon>
        </v-btn>
      </template>
      <div class="the-menu pa-2 white" >
      <v-btn elevation="0" class="justify-start caption" text tile width="100%">ELECTRONICE</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">BOOK & MAGAZEN </v-btn>
         <v-btn elevation="0" class="justify-start caption" text tile width="100%">GIFT</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">SPORT & FITNESS</v-btn>
         <v-btn elevation="0" class="justify-start caption" text tile width="100%">COMPUTER & LAPTOP</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">MOVE & MUSIC</v-btn>
          <v-btn elevation="0" class="justify-start caption" text tile width="100%">FOOD & DRINK</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">BUETY & HEALTHY</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">KITCHEN</v-btn>
            <v-btn elevation="0" class="justify-start caption" text tile width="100%">SPORT & FITNESS</v-btn>
         <v-btn elevation="0" class="justify-start caption" text tile width="100%">COMPUTER & LAPTOP</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">BABY CARE & TOYS</v-btn>
           <v-btn elevation="0" class="justify-start caption" text tile width="100%">FOOD & DRINK</v-btn>
           <v-btn elevation="0" class="justify-start caption" text tile width="100%">BOOK & MAGAZEN </v-btn>
         <v-btn elevation="0" class="justify-start caption" text tile width="100%">GIFT</v-btn>
        <v-btn elevation="0" class="justify-start caption" text tile width="100%">BUETY & HEALTHY</v-btn>
    </div>
    </v-menu>
               </v-col>
               <v-col cols="9 pl-0"> 
                 <v-text-field
                 style="border-radius:0;font-size:11px!important;"
              dense
              color="grey"
            outlined
            label="Search item.."
            append-icon="mdi-search-web"
          ></v-text-field>
          </v-col>
             </v-row>
          </v-col>
          <v-col cols="6" md="3" class="d-none d-md-block" >
            <v-row class="telephone  ml-auto" style="width:80%">
              <v-col cols="4" class="d-inline-block text-right">
                <v-icon x-large color="#009688">mdi-phone-classic</v-icon>
              </v-col>
              <v-col cols="8" class=" d-inline-block px-0 text-left">
                <p class="mb-0">HOTLINE</p>
                <p class="caption">(801)2345-876</p>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"header2",
    data: () => ({
    hover:'false'
  }),
}
</script>
<style >
.header2 .row {
  height: 100%;
  margin-top: 0px;
}
.header2 .theme--light.v-icon{
    color: #009688;
}
.v-text-field__details{
  display: none!important;
}
.telephone{
  width: 50%;
}
@media (max-width: 960px) { 
  .header2 .container .row div{
    padding-top: 0px;
    padding-bottom: 3px;
  }
  .header2 .container .title-store{
    text-align: center!important;
}
 }
 @media (min-width: 992px) { 
.header2 .container{
  padding-top: 0px;
  padding-bottom: 0px;
}
 }
@media (max-width: 768px) { 
 }
@media (max-width: 576px) { 
 }
.header2 .categ{
color: grey;
width: 100%;
border: 1px solid rgb(146, 146, 146);
font-size: 11px!important;
border-right: 0;
padding: 0;
}
.header2 .the-menu{
  background-color: white!important;
}
</style>