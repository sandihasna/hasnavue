<template>
  <div class="home">
   <Header />
   <Hero />
   <Women />
   <Instagram />
   <LogoPartner />
   <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Women from '@/components/Women.vue'
import Instagram from '@/components/Instagram.vue'
import LogoPartner from '@/components/LogoPartner.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    Hero,
    Women,
    Instagram,
    LogoPartner,
    Footer
  }
}
</script>
