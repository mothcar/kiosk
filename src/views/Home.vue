<template>
  <v-container>
    test
    <v-btn @click="goDub">go Duplicate</v-btn>
  </v-container>
</template>

<script>
  // import HelloWorld from '../components/HelloWorld'

  export default {
    name: 'Home',

    components: {
      
    },

    methods: {
      goDub() {
        this.$router.push('/test')
      }
    }
  }
</script>
