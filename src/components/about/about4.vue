<template>
    <div class="about4">
        <v-container>
            <v-row>
                <v-col cols="12" sm="6">
                    <a href="#"><v-img src="@/assets/about/e.png"></v-img></a>
                </v-col>
                <v-col cols="12" sm="6">
                    <a href="#"><v-img src="@/assets/about/ee.png"></v-img></a>
                    <v-row class="ma-0 mt-3" >
                        <v-col cols="6 pl-0 pb-0">
                            <a href="#"><v-img height="100%" src="@/assets/about/eee.png"></v-img></a>
                        </v-col>
                        <v-col cols="6 pr-0 pb-0">
                            <a href="#"><v-img height="100%" src="@/assets/about/eeee.png"></v-img></a>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"about4",
}
</script>
<style scoped>
@keyframes move2 {
    0%{
        transform: translateY(0);
    }
    100%{
        transform: translateY(5px);
    }
}
.about4 .v-image:hover{
animation: move2 infinite linear alternate .3s;
}
</style>