<template>
    <div class="home4 my-8">
           <v-row class="ma-0">
               <v-col cols="12" sm="4" class="pa-0">
                   <v-img src="@/assets/home/home4/e.jpg" style="position:relative" class="my-img">
                   <div class="back"></div>
                   <v-row justify="center" align="center" style="height:100%">
                   <div class="inner-text pt-5">
                       <h3>Decorations</h3>
                       <hr style="width:50px" class="mx-auto mb-1">
                       <p class="mb-1">20 items</p>
                       <v-btn color="#009688" dark tile small>Shop Now</v-btn>
                       </div>
                       </v-row>
                    </v-img>
               </v-col>
               <v-col cols="12" sm="4" class="pa-0">
                    <v-img src="@/assets/home/home4/ee.jpg" style="position:relative" class="my-img">
                   <div class="back"></div>
                   <v-row justify="center" align="center" style="height:100%">
                   <div class="inner-text pt-5">
                       <h3>Houseware</h3>
                       <hr style="width:50px" class="mx-auto mb-1">
                       <p class="mb-1">10 items</p>
                       <v-btn color="#009688" dark tile small>Shop Now</v-btn>
                       </div>
                       </v-row>
                    </v-img>
               </v-col>
               <v-col cols="12" sm="4" class="pa-0">
                 <v-img src="@/assets/home/home4/eee.jpg" style="position:relative" class="my-img">
                   <div class="back"></div>
                   <v-row justify="center" align="center" style="height:100%">
                   <div class="inner-text pt-5">
                       <h3>Furniture</h3>
                       <hr style="width:50px" class="mx-auto mb-1">
                       <p class="mb-1">14 items</p>
                       <v-btn color="#009688" dark tile small>Shop Now</v-btn>
                       </div>
                       </v-row>
                    </v-img>
               </v-col>
           </v-row>
           <v-container class="mt-5 imges">
               <v-row>
                   <v-col cols="6" sm="3">
                       <v-img src="@/assets/home/home4/z.jpg"></v-img>
                   </v-col>
               <v-col cols="6" sm="3"><v-img src="@/assets/home/home4/zz.jpg"></v-img></v-col>
               <v-col cols="6" sm="3"><v-img src="@/assets/home/home4/zzz.jpg"></v-img></v-col>
               <v-col cols="6" sm="3"><v-img src="@/assets/home/home4/zzzz.jpg"></v-img></v-col>
               </v-row>
           </v-container>
        </div>
</template>
<script>
export default {
    name:"home4",

}
</script>
<style >
@keyframes move1 {
    0%{
        transform: translateY(0);
    }
    100%{
        transform: translateY(5px);
    }
}
.home4 .inner-text{
    color: white;
    text-align: center;
    z-index: 3;
}
.home4 .back{
    width: 0%;
    height: 0%;
    background-color: rgba(0, 0, 0, 0.699);
    position: absolute;
    top: 50%;
    left: 50%;
    z-index: 2;
    transition: all .4s linear;
}
.home4 .my-img:hover .back{
    width: 80%;
    height: 80%;
    top: 10%;
    left: 10%;
}
.home4 .imges .v-image:hover{
    cursor: pointer;
    animation: move1 infinite linear alternate .2s;
}
</style>