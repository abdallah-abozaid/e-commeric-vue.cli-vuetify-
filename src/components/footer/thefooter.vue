<template>
    <div class="thefooter mt-10 black lighten-3">
        <v-container>
            <v-row class="ma-0 pt-6">
            <v-col cols="12 fst" sm="6" md="3" style="border-right:1px solid grey" order="1" order-md="1">
                <p class="text-left display-1 font-weight-bold white--text" > 
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
          </p>
          <p class="white--text caption">Lorem ips mollitia, laudantium laboriosam beatae delectus nobis atque dolorem doloremque ut aut eum magni temporibus magnam maxime natus facere et. Tempore, necessitatibus!</p>
            </v-col>
            <v-col cols="6 " sm="6" md="3" style="border-right:1px solid grey" order="3" order-md="2">
                <p class="text-left text-h5 font-weight-bold white--text" >MY ACCOUNT</p>
                <v-btn plain color="white" class="d-block body-2 "> <v-icon>mdi-chevron-double-right</v-icon> Contact Us</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> My Account</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> ChechOut</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> View Cart</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> Product Listing</v-btn>
            </v-col>
            <v-col cols="6" sm="6" md="3" style="border-right:1px solid grey" order="4" order-md="3" >
                <p class="text-left text-h5 font-weight-bold white--text" >INFORMATION</p>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> About Us</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> Team Of Use</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> Clup Info & FAQ's</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> Privcy Policy</v-btn>
                <v-btn plain color="white" class="d-block body-2"> <v-icon>mdi-chevron-double-right</v-icon> Contact Us</v-btn>
            </v-col>
            <v-col cols="12" sm="6" md="3" class="white--text" order="2" order-md="4">
                <p class="text-left text-h5 font-weight-bold white--text">Contact Us</p>
                <p class="caption"><v-icon color="#009688">mdi-home</v-icon> 8901 Marmora Road, Glasgow, D04 89GR</p>
                <p class="caption"><v-icon color="#009688">mdi-cellphone-android</v-icon> Telephone: (801) 2345 - 6789</p>
                <p class="caption"><v-icon color="#009688">mdi-email</v-icon> E-mail: support@maxshop.com</p>
            </v-col>
        </v-row>
        </v-container>
        <p class="grey lighten-2 caption mb-0 text-center">opyright © 2020 SW MaxShop Store. All Rights Reserved. Design by WpThemeGo.com</p>
    </div>
</template>
<script>
export default {
    name:"thefooter",
}
</script>
<style scoped>
@media (max-width: 576px) { 
.thefooter .fst{
    border: none!important;
}

}
</style>