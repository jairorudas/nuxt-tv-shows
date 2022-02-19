<template>
  <base-layout>
    <template slot="header">
      <NavBar />
    </template>
    <template #main> 
      <h4 id="titleSeries">Series</h4>
       <SeriesNet/>
     </template>
    <template #footer>footer</template>
  </base-layout>
</template>

<script>
import BaseLayout from '@/atomic/templates/BaseLayout.vue'
import NavBar from '@/atomic/organism/Navbar'
import { SeriesNet }  from '@/atomic/atoms/'

export default {
    name: 'NSeries',
    components: {BaseLayout, NavBar, SeriesNet}

}
</script>

<style lang="postcss">

   #titleSeries{
margin: 1em;
   }

</style>
