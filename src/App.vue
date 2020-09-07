<template>
  <v-app>
    <Navbar>Loading Navbar component...</Navbar>
    <v-main>
      <v-content>
        <router-view></router-view>
      </v-content>
    </v-main>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar'

export default {
  name: 'App',

  components: {
    Navbar
  },

  data: () => ({
    //
  })
}
</script>
