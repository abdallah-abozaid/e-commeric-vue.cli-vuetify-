<template>
    <div class="about1 mb-12">
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
            <div class="second grey lighten-4 py-5">
                  <v-container>
                        <v-img src="@/assets/about/a.jpg"  class="the-img float-left mr-5"></v-img>
                        <h2 class="mb-8 mt-5">About Us</h2>
                       <p class="caption">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora, quae architecto. Enim deleniti exercitationem quibusdam culpa itaque, nihil facilis laudantium ipsam, expedita fuga dignissimos sapiente vero, vitae ut minima inventore?</p>
                       <p class="mb-0 caption">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora, quae architecto. Enim deleniti exercitationem quibusdam culpa itaque, nihil facilis laudantium ipsam, expedita fuga dignissimos sapiente vero, vitae ut minima inventore?</p>
                       <p class="caption">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora, quae architecto. Enim deleniti exercitationem quibusdam culpa itaque, nihil facilis laudantium ipsam, expedita fuga dignissimos sapiente vero, vitae ut minima inventore?</p>
             </v-container>
            </div>
    </div>
</template>
<script>
export default {
    name:"about1",
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: 'http://localhost:8080/',
        },
        {
          text: 'About Us',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
}
</script>
<style>
 .v-application ul, .v-application ol{
    padding-left: 3px!important;
}
.v-breadcrumbs{
    display: inline-block!important;
}
.v-breadcrumbs li:first-of-type a{
    color: black!important;
}


@media (max-width:700px){
.about1 .v-image{
    float:none!important;
    width: 80%;
    margin: 0px auto 10px!important;
}
.about1 .second h2{
    margin-bottom: 0px!important;
}
.about1 .second p{
    font-size: 11px!important;
}
}
</style>