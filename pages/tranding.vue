<template>
  <base-layout>
    <template slot="header">
      <NavBar />
    </template>
    <template #main>Mas vistos</template>
    <template #footer>footer</template>
  </base-layout>
</template>

<script>
  import BaseLayout from '@/atomic/templates/BaseLayout.vue'
  import NavBar from '@/atomic/organism/Navbar'
  export default {
    name: 'NTranding',
    components: {BaseLayout, NavBar}
  }
</script>

<style lang="postcss">
 
</style>
