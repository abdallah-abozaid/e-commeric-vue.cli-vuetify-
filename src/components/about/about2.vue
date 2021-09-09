<template>
    <div class="about2 py-10">
        <v-container>
            <div class="clints">
                    <h2>WHAT CLIENT SAY</h2>

 <v-item-group
        v-model="onboarding"
        class="text-center"
        mandatory
      >
        <v-item
          v-for="n in length"
          :key="`btn-${n}`"
          v-slot="{ active, toggle }"
        >
          <v-btn
            :input-value="active"
            icon
            @click="toggle"
          >
            <v-icon>mdi-record</v-icon>
          </v-btn>
        </v-item>
      </v-item-group>

                    <v-window v-model="onboarding" class="mt-3" vertical>
                        <v-window-item >
                            <p class="caption mb-1"> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nesciunt quisquam quo labore natus, perferendis quam deleniti a totam optio rem, autem iusto ut. Doloribus maiores eius nesciunt, eveniet ab culpa!</p>
                            <h4>MARK BALY</h4>
                            <v-icon>mdi-minus</v-icon><span class="mx-2">Leader</span><v-icon>mdi-minus</v-icon>
                        </v-window-item>
                        <v-window-item >
                            <p class="caption mb-1"> Lorem ipsum dolor sit, amet consectetur adipisicing  sit, amet consectetur adipisicing elit. Nesciunt quisquam quo labore natus, perferendis quam deleniti a totam optio rem, autem iusto ut. Doloribus maiores eius nesciunt, eveniet ab culpa!</p>
                            <h4>ABDALLAH</h4>
                            <v-icon>mdi-minus</v-icon><span class="mx-2">DEVELOPER</span><v-icon>mdi-minus</v-icon>
                        </v-window-item>
                        <v-window-item >
                            <p class="caption mb-1"> Lorem ipsum dolor sit, adipisicing elit. Nesciunt quisquam quo labore natus, perferendis quam deleniti a totam optio rem, autem iusto ut. Doloribus maiores eius nesciunt, eveniet ab culpa!</p>
                            <h4>MAHA</h4>
                            <v-icon>mdi-minus</v-icon><span class="mx-2">TEACHER</span><v-icon>mdi-minus</v-icon>
                        </v-window-item>
                        <v-window-item >
                            <p class="caption mb-1"> Lorem ipsum dolor sit, amet consectetur amet consectetur adipamet consectetur adipamet consectetur adipadipisicing elit. Nesciunt quisquam quo labore natus, perferendis quam deleniti a totam optio rem, autem iusto ut. Doloribus maiores eius nesciunt, eveniet ab culpa!</p>
                            <h4>HAMZA</h4>
                            <v-icon>mdi-minus</v-icon><span class="mx-2">STYLIST</span><v-icon>mdi-minus</v-icon>
                        </v-window-item>
                        <v-window-item >
                            <p class="caption mb-1"> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nesciunt quamet consectetur adipamet consectetur adipamet consectetur adipamet consectetur adipamet consectetur adipisquam quo labore natus, perferendis quam deleniti a totam optio rem, autem iusto ut. Doloribus maiores eius nesciunt, eveniet ab culpa!</p>
                            <h4>OSAMA</h4>
                            <v-icon>mdi-minus</v-icon><span class="mx-2">DESIGNER</span><v-icon>mdi-minus</v-icon>
                        </v-window-item>
    
                        </v-window>
            </div>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"about2",
    data: () => ({
      length: 5,
      onboarding: 0,
    }),
}
</script>
<style scoped>
.about2 .clints{
    border: 1px dashed grey;
    padding: 20px 0;
    text-align: center;
}
.about2 .clints h2{
width: 265px;
background-color: white;
margin:-40px auto 20px;
}
.about2 .v-item--active{
color:grey!important;
}
.about2 .theme--light.v-btn.v-btn--icon{
    color: rgb(204, 204, 204);
    margin-left: 0px!important;
}
.about2 .v-btn--icon.v-size--default{
    width: 22px!important;
    transform: scale(.8);
}
.about2 .theme--light.v-btn--active:hover::before,.about2 .theme--light.v-btn--active::before{
    opacity: 0;
}
</style>