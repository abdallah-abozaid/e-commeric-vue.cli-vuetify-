<template>
  <div class="about">
    <about-1/>
    <about-4/>
    <about-5/>
       <about-2/>
  <about-3/>

  </div>
</template>
<script>
import about1 from '../components/about/about1.vue'
import About2 from '../components/about/about2.vue'
import About3 from '../components/about/about3.vue'
import About4 from '../components/about/about4.vue'
import About5 from '../components/about/about5.vue'
export default {
  components: { about1, About2, About3, About4, About5 },
  name:"about"
}
</script>