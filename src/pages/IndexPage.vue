<template>
  <q-page class="flex flex-center">
    <ProductCard/>
<!--    produtos devem vir aqui?-->
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import ProductCard from '../components/ProductCard.vue'

export default defineComponent({
  name: 'IndexPage',
  components:{ProductCard}
})
</script>
