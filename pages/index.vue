<template>
  <div class="px-3 font-poppins">
    <NavBar />
    <main>
       <Banner />
       <Services />
       <Designs />
    </main>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import Banner from '@/components/Banner.vue'
import Services from '@/components/Services.vue'
import Designs from '@/components/Designs.vue'

export default {
  components: { NavBar, Banner, Services, Designs }

}
</script>
