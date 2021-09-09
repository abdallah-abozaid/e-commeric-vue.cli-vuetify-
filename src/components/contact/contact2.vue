<template>
    <div class="contact2 mt-10">
        <v-container>
            <v-row>
                <v-col cols="12" sm="5">
                    <h2 class="mb-3">Contact Us</h2>
                    <p class="caption">Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis expedita ex quibusdam voluptas maxime vitae tenetur sequi praesentium quos. Tenetur officiis corporis ratione repellendus ad necessitatibus pariatur quae laboriosam hic?</p>
                    <p class="caption">Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis expedita ex quibusdam voluptas maxime vitae tenetur sequi praesentium quos.?</p>
                    <p class="caption mb-0 pb-2" style="border-bottom:1px dashed grey"><v-icon>mdi-map-marker-multiple</v-icon> 123 Suspendis mattis, Sollicitudin District,Accums Fringilla</p>
                    <p class="caption mb-0 py-2" style="border-bottom:1px dashed grey"><v-icon>mdi-email</v-icon> Email : support@domainstore.com</p>
                    <p class="caption mb-0 py-2" style="border-bottom:1px dashed grey"><v-icon>mdi-phone-classic</v-icon> Hotline : 0123456789</p>
               <div class="icons text-center">
                    <v-btn text icon tile x-large><v-icon>mdi-facebook</v-icon></v-btn>
                <v-btn text icon tile x-large><v-icon>mdi-twitter</v-icon></v-btn>
                <v-btn text icon tile x-large><v-icon>mdi-wifi</v-icon></v-btn>
                <v-btn text icon tile x-large><v-icon>mdi-youtube-subscription</v-icon></v-btn>
                <v-btn text icon tile x-large><v-icon>mdi-alpha-v-box</v-icon></v-btn>
               </div>
                </v-col>
                <v-col cols="12" sm="7">
                        <h2 class="mb-3">Send Your Commets</h2>
                        <v-text-field
            label="Your Name"
            prepend-icon="mdi-account-box"
          ></v-text-field>
                        <v-text-field
            label="Your Email"
            prepend-icon="mdi-email"
          ></v-text-field>
                        <v-text-field
            label="Subject"
            prepend-icon="mdi-account-question-outline"
          ></v-text-field>
                        <v-textarea
            label="Your Commets"
            prepend-icon="mdi-subtitles"
          ></v-textarea>
          <v-btn class="pa-6 grey"><v-icon left>mdi-send-check</v-icon> SEND EMAIL</v-btn>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>
<script>
export default {
    name:"contact",
}
</script>
<style scoped>
.icons .v-btn:hover{
    color: red;
}
</style>