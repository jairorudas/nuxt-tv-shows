<template>
  <base-layout>
    <template slot="header">
      <NavBar />
    </template>
    <template #main>SERIES</template>
    <template #footer>footer</template>
  </base-layout>
</template>

<script>
import BaseLayout from '@/atomic/templates/BaseLayout.vue'
import NavBar from '@/atomic/organism/Navbar'

export default {
    name: 'NSeries',
    components: {BaseLayout, NavBar}

}
</script>

<style lang="postcss">
   
</style>
