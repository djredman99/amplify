<template>
  <div class="home">
    <home-hero></home-hero>
    <campaign-cards></campaign-cards>
  </div>
</template>

<script>
import HomeHero from '@/components/HomeHero.vue'
import CampaignCards from '@/components/CampaignCards'

export default {
  name: 'Home',
  components: {
    HomeHero,
    CampaignCards
  }
}
</script>
