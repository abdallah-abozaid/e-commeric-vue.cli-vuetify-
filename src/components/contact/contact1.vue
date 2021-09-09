<template>
    <div class="contact1">
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
              <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d5417.768858010852!2d-0.18718371716784138!3d51.49380360754139!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sar!2s!4v1630533352260!5m2!1sar!2s"  width="100%" height="260px" style="border:1px dashed grey; box-shadow:2px 2px 10px grey" allowfullscreen="" loading="lazy"></iframe>
    </div>
</template>
<script>
export default {
    name:"contact1",
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: 'http://localhost:8080/',
        },
        {
          text: 'Contact Us',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
}
</script>
<style >
 .v-application ul, .v-application ol{
    padding-left: 3px!important;
}
.v-breadcrumbs{
    display: inline-block!important;
}
.v-breadcrumbs li:first-of-type a{
    color: black!important;
}

</style>