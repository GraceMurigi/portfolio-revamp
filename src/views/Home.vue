<template>
  <v-container >
    <v-row no-gutters>
      <v-col >
        <v-img 
        src="@/assets/me.svg" 
        contain
        class="profile-pic"
        ></v-img>
      </v-col>
      <v-col align-self="center">
        <h1 >Hi there...</h1>
        <h2 >I'm Grace Murigi</h2>
        <h3 >A web developer from Kenya</h3>

        <v-btn dark flat class="pink darken-4">Resume</v-btn>
      </v-col>
    </v-row>
  </v-container>
  
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    
  }
}
</script>

<style scoped>
    
   
    .profile-pic {
      height: 80%;
      width: 80%;
      /* border-radius: 50%; */
      /* background-color:; */
    }
</style>
