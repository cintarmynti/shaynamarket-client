<template>
  <div class="home">
      <header-shayna-vue/>
      <hero-shayna-vue/>
      <banner-shayna-vue/>
      <insta-shayna-vue/>
      <partner-shayna-vue/>
      <footer-shayna-vue/>
  </div>
</template>

<script>
import HeaderShaynaVue from '@/components/HeaderShayna.vue'
import HeroShaynaVue from '@/components/HeroShayna.vue'
import BannerShaynaVue from '@/components/BannerShayna.vue'
import InstaShaynaVue from '@/components/InstaShayna.vue'
import PartnerShaynaVue from '@/components/PartnerShayna.vue'
import FooterShaynaVue from '@/components/FooterShayna.vue'
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderShaynaVue,
    HeroShaynaVue,
    BannerShaynaVue,
    InstaShaynaVue,
    PartnerShaynaVue,
    FooterShaynaVue
  }
}
</script>
