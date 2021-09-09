<template>
<div class="home mt-7">
<home-1/>
<home-2/>
<home-4/>
<home-3/>
<home-7/>
<home-5/>
<home-6/>

</div>
</template>

<script>
import Home1 from '../components/home/home1.vue';
import Home2 from '../components/home/home2.vue';
import Home3 from '../components/home/home3.vue';
import Home4 from '../components/home/home4.vue';
import Home5 from '../components/home/home5.vue';
import Home6 from '../components/home/home6.vue';
import Home7 from '../components/home/home7.vue';

export default {
  name: "Home",

  components: {
    Home1,
    Home2,
    Home3,
    Home4,
    Home5,
    Home6,
    Home7,
  },
};
</script>
