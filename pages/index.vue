<template>
  <div class="px-3 font-poppins">
    <NavBar />
    <main>
       <Banner />
       <Services />
    </main>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import Banner from '@/components/Banner.vue'
import Services from '@/components/Services.vue'

export default {
  components: { NavBar, Banner, Services }

}
</script>
