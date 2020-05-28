
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
      name: 'Bottomslider',
    data () {
      return {
        items: [
          {
            src: require('../assets/images/bs1.png'),
          },
          {
            src: require('../assets/images/bs2.png'),
          },
          {
            src: require('../assets/images/bs3.png'),
          },
          {
            src: require('../assets/images/bs4.png'),
          },
        ],
      }
    },
  }
</script>

