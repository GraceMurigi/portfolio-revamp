<template>
    <span>
        <!-- <v-navigation-drawer app v-model="drawer" class="pink lighten-5" >
            <v-list>
                <v-list-item-group>
                    <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content>
                            <v-list-item-title v-text="item.title"></v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>
                     
                </v-list-item-group>
            </v-list>
        </v-navigation-drawer> -->
        <v-app-bar app class="pink lighten-5">
            <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-app-bar-nav-icon>
            <v-tabs
            class=" nav-text"
            color="pink darken-4"
            left
            
            >
                <v-tab v-for="(item, i) in items" :key="i" :to="item.route">{{item.title}}</v-tab>
                
            </v-tabs>
        </v-app-bar>
    </span>

    
    <!-- <span>
        
        
        <v-navigation-drawer app v-model="drawer" class="blue" >
            <v-list>
                <v-list-item-group>
                    <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content>
                            <v-list-item-title v-text="item.title"></v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>
                     
                </v-list-item-group>
            </v-list>
        </v-navigation-drawer>
        <v-toolbar app color="blue darken-4" dark>
            <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-app-bar-nav-icon>
            <v-spacer class="hidden-md-and-up"></v-spacer>
            <v-toolbar-title>{{appTitle}}</v-toolbar-title>
            <v-spacer class="hidden-sm-and-down"></v-spacer>
            <v-btn text class="hidden-sm-and-down">Home</v-btn>
             <v-btn text class="hidden-sm-and-down">Skils</v-btn>
            <v-btn flat color="brown lighten-3" class="hidden-sm-and-down">Hire me</v-btn>
        </v-toolbar>

    </span> -->
    

</template>

<script>
export default {
    name: 'AppNavigation',

    data() {
        return { 
            appTitle: "Meal Prep",
            drawer: false,
            items: [
                {title: 'Home', route:'/'},
                {title: 'Skills', route:'/skills'},
                {title: 'Projects', route:'/projects' },
                
            ]
        };
    }
};
</script>

<style scoped>
    .nav-text {
        color: #31383F;
    }
</style>