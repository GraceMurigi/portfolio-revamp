<template>
  <v-footer
    dark
    padless
  >
    <v-card
      flat
      tile
      class="pink darken-4 white--text text-center"
      width="100%"
    >
      <v-card-text>

        <v-btn
          v-for="(icon, i) in icons"
          :key="i"
          :href="icon.link"
          class="mx-4 white--text"
          icon
          target="_blank"
        >
          <v-icon size="24px">{{ icon.symbol }}</v-icon>
        </v-btn>
      </v-card-text>

    
      <v-divider></v-divider>

      <v-card-text class="white--text">
        <strong>Grace Murigi</strong>—{{ new Date().getFullYear() }}  
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      icons: [
          {symbol:'mdi-linkedin', link:"https://www.linkedin.com/in/grace-murigi/"},
          {symbol:'mdi-twitter', link:"https://twitter.com/murigi_"}
       
      ],
    }),
  }
</script>