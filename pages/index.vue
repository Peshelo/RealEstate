<template>
  <div class="div">
     <FIlters/>
     <ProductList/>
  </div>
 
</template>

<script>
import FIlters from '../components/filters/FIlters.vue';
import ProductList from '../components/Home/ProductList.vue';

export default {
    name: "IndexPage",
    components: { FIlters, ProductList }
}
</script>
