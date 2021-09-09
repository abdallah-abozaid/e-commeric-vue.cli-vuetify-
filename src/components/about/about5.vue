<template>
    <div class="about5 mb-10">
            <v-row class="ma-0">
                <v-col cols="12" sm="6">
                    <v-img src="@/assets/about/dd.png" style="position:relative" class="my-img">
                   <div class="back"></div>
                   <v-row justify="center" align="center" style="height:100%">
                   <div class="inner-text pt-5">
                       <h1>Welcome to Maxshop</h1>
                       <p class="mb-1 caption">Claritas est etiam processus dynamicus, qui sequitur mutationem consuetudium lectorum. Mirum est notare quam littera gothica, quam nunc putamus parum claram, anteposuerit litterarum formas humanitatis per seacula quarta decima decima futurum.</p>
                       <v-btn color="#009688" dark tile small>More About Us..</v-btn>
                       </div>
                       </v-row>
                    </v-img>
                </v-col>
                <v-col cols="12" sm="6">
                    <v-img src="@/assets/about/d.png" style="position:relative" class="my-img">
                   <v-row justify="center" align="center" style="height:100%">
                   <div class="text-center white--text pt-5">
                       <h1 class="display-3">SEASON SALE</h1>
                       <h2 class="mb-1 ">Save up to 40% discounts</h2>
                       <v-btn color="#009688" dark tile small>More About Us..</v-btn>
                       </div>
                       </v-row>
                    </v-img>
                </v-col>
            </v-row>
    </div>
</template>
<script>
export default {
    name:"about5",
}
</script>
<style scoped>
.about5 .inner-text{
    color: black;
    text-align: center;
    z-index: 3;
    width: 70%;
}
.about5 .back{
   width: 80%;
    height: 80%;
    top: 10%;
    border: 1px solid rgba(128, 128, 128, 0.473);
    box-shadow: 2px 2px 6px rgba(128, 128, 128, 0.473);
    left: 10%;
    background-color: rgba(255, 255, 255, 0.699);
    position: absolute;
    z-index: 2;
    transition: all .4s linear;
}
</style>