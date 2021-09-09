<template>
    <div class="shop1">
        <v-container>
            <div class="first">
                <v-icon small class="mb-1">mdi-home-assistant</v-icon>
                <v-breadcrumbs
      :items="items"
    >
    <template v-slot:divider>
        <v-icon color="red">mdi-chevron-right</v-icon>
      </template>
    </v-breadcrumbs> 
            </div>
              </v-container>
              <v-container>
                            <v-row>
                                <v-col cols="12" sm="5" md="4">
                                    <v-row class="ma-0">
                                    <v-col cols="6" style="background-color:#009688" class="pb-1 white--text clip pb-0 pr-0">
                                    PRICE</v-col
                                    >
                                <v-col
                                cols="6"
                                class="px-0 text-center py-1"
                                    style="border-bottom: 3px solid #009688; margin-left: -3px"
                                >
                        </v-col>
                        </v-row>
                        <v-card tile outlined class="pa-2 pb-8">
                           <v-range-slider
            v-model="range"
            :max="max"
            :min="min"
            hide-details
            color="#009486"
            class="align-center d-block my-5"
          >
           </v-range-slider>
           <v-row >
               <v-col class="pa-0">
                   <v-text-field
                :value="range[0]"
                class="pt-0 mx-1 ml-3 d-inline-block"
                outlined
                dense
                type="number"
                label="min "
                @change="$set(range, 0, $event)"
              ></v-text-field>
              </v-col>
               <v-col class="pa-0">
                   <v-text-field
                :value="range[1]"
                class="pt-0 mx-1 d-inline-block"
                outlined
                dense
                label="max"
                type="number"
                @change="$set(range, 1, $event)"
              ></v-text-field>
               </v-col>
               <v-col class="pa-0 pr-1">
                   <v-btn color="#009486" class="mx-1" height="40px" dark>Filter</v-btn>
               </v-col>
           </v-row>
                        </v-card>
                      </v-col>
                      <v-col cols="12" sm="7" md="8" style="display: flex;align-items: flex-end;">
                          <v-img src="@/assets/shop/a.png"></v-img>
                      </v-col>
                  </v-row>
              </v-container>
    </div>
</template>
<script>
export default {
    name:"shop1",
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: 'http://localhost:8080/',
        },
        {
          text: 'Shop',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
      min: 50,
        max: 1000,
        range: [100, 350],
    }),
}
</script>
<style >

</style>