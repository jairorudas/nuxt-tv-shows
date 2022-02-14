<template>
  <base-layout>
    <template slot="header">
      <NavBar />
    </template>
    <template #main>
      <MainVideoPlayer/>
    </template>
    <template #footer>footer</template>
  </base-layout>
</template>

<script>
import BaseLayout from '@/atomic/templates/BaseLayout.vue'
import NavBar from '@/atomic/organism/Navbar'
import { MainVideoPlayer } from '@/atomic/atoms'

export default {
  name: 'IndexPage',
  components: {BaseLayout, NavBar, MainVideoPlayer},
  async asyncData({$axios}) {
    const sugestionsFilms = await $axios.$get('https://api.tvmaze.com/search/shows?q=girls')    
    return sugestionsFilms
  },
  data: () => ({})
}
</script>
