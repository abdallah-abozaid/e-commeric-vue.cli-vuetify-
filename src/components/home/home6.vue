<template>
    <div class="home6 mt-10">
        <v-container>
            <v-row>
                <v-col cols="12" sm="6" md="4">
                    <v-card ><v-img src="@/assets/home/home6/z.png"></v-img></v-card>
                </v-col>
                <v-col cols="12" sm="6" md="4">
                    <v-card><v-img src="@/assets/home/home6/zz.png"></v-img></v-card>
                </v-col>
                <v-col cols="12" sm="6" md="4" class="last">
                    <v-card><v-img src="@/assets/home/home6/zzz.png"></v-img></v-card>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"home6",
}
</script>
<style scoped>
@keyframes move2 {
    0%{
        transform: translateX(0);
    }
    100%{
        transform: translateX(5px);
    }
}
.home6 .v-card{
    border: 3px solid rgb(196, 196, 196);
    cursor: pointer;
}
.home6 .v-card:hover{
animation: move2 infinite linear alternate .4s;
}
@media (min-width: 600px) and (max-width: 960px) {
.home6 .last{
    margin: auto;
}
}
</style>