<template>
    <div class="contact">
        <contact-1/>
        <contact-2/>
    </div>
</template>
<script>
import contact1 from '../components/contact/contact1.vue'
import Contact2 from '../components/contact/contact2.vue'
export default {
  components: { contact1, Contact2 },
    name:"contact",
    
}
</script>