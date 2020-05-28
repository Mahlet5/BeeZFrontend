<template>
  <v-app>
    <v-app-bar
      app
      flat
    >
       <Header/>
    </v-app-bar>

    <v-content>
     <Topslider/>
     <div class="row">
     <div class="col-6">
        <Bottomslider/>
     </div>

      <div class="col-6">
        
     </div>
     </div>
    </v-content>

  </v-app>
</template>

<script>
import Header from './components/Header';
import Topslider from './components/Topslider';
import Bottomslider from './components/Bottomslider';

export default {
  name: 'App',

  components: {
    Header,
    Topslider,
    Bottomslider
  },

  data: () => ({
    //
  }),
};
</script>
