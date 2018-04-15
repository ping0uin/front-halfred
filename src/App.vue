<template>
  <div id="app">
    <v-app>
      <NavBar/>
      <v-content>
        <v-container>
          <router-view/>
        </v-container>
      </v-content>
      <FootLinks/>
    </v-app>
  </div>
</template>

<script>
import NavBar from './components/NavBar';
import FootLinks from './components/FootLinks';

export default {
  name: 'App',
  components: {
    NavBar,
    FootLinks,
  },
};
</script>

<style>

</style>
