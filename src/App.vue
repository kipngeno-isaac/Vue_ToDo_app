<template>
<!-- App.vue -->

<v-app>

  <v-app-bar 
  app
  color = "primary-blue"
  dark
  >

  <v-toolbar-title>TODO APP</v-toolbar-title>
    
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <to-do></to-do>
    </v-container>
  </v-main>

  <v-footer app>
    <!-- -->
  </v-footer>
</v-app>
</template>

<script>
import ToDo from './components/ToDoItem.vue';

export default {
  name: 'App',

components:{
  ToDo
},

  data: () => ({
    //
  }),
};
</script>
