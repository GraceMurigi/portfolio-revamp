<template>
 
  <v-app>
    <site-navigation></site-navigation>

    <v-main class="pink  lighten-5">
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-main>

    <site-footer></site-footer>

   
  </v-app>
</template>

<script>
import SiteNavigation from '@/components/SiteNavigation'
import SiteFooter from '@/components/SiteFooter'



export default {
  name: 'App',

  components: {
    SiteNavigation,
    SiteFooter
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
  

</style>
