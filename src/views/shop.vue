<template>
    <div class="shop">
        <shop-1/>
        <shop-2/>
    </div>
</template>
<script>
import shop1 from '../components/shop/shop1.vue'
import Shop2 from '../components/shop/shop2.vue'
export default {
  components: { shop1, Shop2 },
    name:"shop",
}
</script>