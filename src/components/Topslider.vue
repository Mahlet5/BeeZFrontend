
 <template>
   
  <v-carousel hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
    
</template>


<script>
  export default {
      name: 'Topslider',
    data () {
      return {
        items: [
          {
            src: require('../assets/images/TS1@2x.png'),
          },
          {
            src: require('../assets/images/TS2@2x.png'),
          },
          {
            src: require('../assets/images/TS3@2x.png'),
          },
          {
            src: require('../assets/images/TS4@2x.png'),
          },
        ],
      }
    },
  }
</script>

