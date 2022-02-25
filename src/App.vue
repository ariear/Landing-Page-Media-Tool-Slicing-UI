<template>
<div class="relative">
<div class="bg-[#FC881D] clipoutline">
<div class="bg-[#0D0E25] pb-[200px] md:pb-[300px] clipnjir">
  <NavComponent />
  <HeaderComponent />
</div>
</div>
  <img src="/dashboard.png" class="absolute w-[750px] left-0 right-0 top-0 -bottom-[800px] md:-bottom-[1100px] m-auto" alt="">
  </div>
  
  <Kenafah />
  <TerusGimana />
  <Alternative />
  <Footer />
</template>
<script>
import NavComponent from './components/NavComponent.vue'
import HeaderComponent from './components/HeaderComponent.vue'
import Kenafah from './components/Kenafah.vue'
import TerusGimana from './components/TerusGimana.vue'
import Footer from './components/Footer.vue'
import Alternative from './components/Alternative.vue'
export default {
  components: {
    NavComponent,
    HeaderComponent,
    Kenafah,
    TerusGimana,
    Footer,
    Alternative
  }
}
</script>

<style>
  .clipnjir{
    clip-path: polygon(0 0, 100% 0, 100% 98%, 1% 93%);
  }
  .clipoutline{
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0 95%);
  }
</style>