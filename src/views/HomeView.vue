<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
  <v-app>
    <TheNavbar class="index" />
    <TheDashboard />
    <TheFooter />
  </v-app>
</template>

<script>
// @ is an alias to /src
import TheDashboard from '@/components/TheDashboard.vue';
import TheFooter from '@/components/TheFooter.vue';
import TheNavbar from '@/components/TheNavbar.vue';

export default {
  name: 'HomeView',
  components: {
    TheNavbar,
    TheDashboard,
    TheFooter
  }
}
</script>

<style>
.index {
  z-index: 9999;
}
</style>
