<template>
  <v-app>
    <v-app-bar
      app
      flat
    >
       <Header/>
    </v-app-bar>

    <v-content>
   
    </v-content>

  </v-app>
</template>

<script>
import Header from './components/Header';

export default {
  name: 'App',

  components: {
    Header,
  },

  data: () => ({
    //
  }),
};
</script>
