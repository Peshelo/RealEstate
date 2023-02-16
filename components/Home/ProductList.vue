<template>
  <div>
    <div class="grid grid-cols-1 gap-4 py-5 px-5 md:grid-cols-3 md:px-10 xl:grid-cols-4 lg-20">
    <nuxt-link to="/house"><ProductCard/></nuxt-link>
    <ProductCard/>
    <ProductCard/>
    <ProductCard/>
    <ProductCard/>
    <ProductCard/>
  </div>
  <button class="floating bg-gray-800 text-gray-300 py-2 px-4 text-sm rounded-2xl shadow-lg">Open Map</button>

  </div>
  
  
</template>

<script>
import ProductCard from './ProductCard.vue';

export default {
    components: { ProductCard }
}
</script>

<style>
.floating{
  margin: 20px;
  bottom:2;
  left:50%;
  position: sticky;
  position: -webkit-sticky;
  top:0;
  z-index: 4;
}

</style>