<template>
    <v-container> 
        <v-row>
            <v-col cols="12" md="4" >
                <v-card class="elevation-4 " height="400px">
                    <v-img
                    src="@/assets/portfolio/cboard.jpg" 
                    height="200px"
                    ></v-img>
                    <v-card-title>Responsive Landing page project</v-card-title>
                    <v-card-subtitle>Made with HTML & CSS grid. Design by 
                        <a href="https://www.frontendmentor.io/" target="_blank">frontendmentor</a>
                    </v-card-subtitle>
                    <v-card-actions>
                        <v-btn text class="blue--text">
                            <a href="https://clipboard-landing-page-challenge.netlify.app/" target="_blank">View Live</a>
                            </v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="12" md="4">
                <v-card class="elevation-4" height="400px">
                    <v-img
                    src="@/assets/portfolio/weath.png"
                    height="200px"
                    ></v-img>
                    <v-card-title>Weather update app</v-card-title>
                    <v-card-subtitle>Made with Python Flask and the Open weather map API</v-card-subtitle>
                    <v-card-actions>
                        <v-btn text> <a href="http://grace10.pythonanywhere.com/" target="_blank">View Live</a></v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="12" md="4">
                <v-card class="elevation-4" height="400px">
                    <v-img
                    src="@/assets/portfolio/web.png"
                    height="200px"
                    ></v-img>
                    <v-card-title>School Website</v-card-title>
                    <v-card-subtitle>Collaborative project in which I was part of the UI/UX team.</v-card-subtitle>
                    <v-card-actions>
                        <v-btn text> <a href="https://www.thesteppingstoneselementaryschool.sc.ke" target="_blank">View Live</a></v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
          
        </v-row>
        <p class="font-weight-bold text-center">See more on: </p>
        <v-row justify="center">
            <div class="d-flex justify-space-between" >
                <v-tooltip bottom>
                    <template v-slot:activator="{ on, attrs }">
                        <v-btn 
                        text icon v-on="on" v-bind="attrs"
                        class="ma-2 btn" 
                        color="pink darken-4" 
                        href="https://github.com/GraceMurigi" target="_blank">
                            <v-icon>mdi-github</v-icon>
                        </v-btn>
                    </template>
                    <span>Github</span>
                </v-tooltip>

                <v-tooltip bottom>
                    <template v-slot:activator="{ on, attrs }">
                        <v-btn 
                        text icon v-on="on" v-bind="attrs"
                        class="ma-2 btn" 
                        color="pink darken-4" 
                        href="https://codepen.io/ciru" target="_blank">
                            <v-icon>mdi-codepen</v-icon>
                        </v-btn>
                    </template>
                    <span>Codepen</span>
                </v-tooltip>
    
            </div>
            
        </v-row>
    </v-container>
  
</template>

<script>
export default {
    methods: {
        onHover() {

        }
    }
}
</script>

<style scoped>
 


    

</style>