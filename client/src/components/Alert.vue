<template>
<v-layout  column fluid justify-center>
  <v-flex xs3>
<v-alert outline color="error" icon="warning" :value="true">
      Vous devez être connecté pour créer une recette
    </v-alert>
    </v-flex>
    </v-layout>
   
</template>

<script>

export default {
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
