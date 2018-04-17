<template>
    <v-toolbar>
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title id="mainTitle">Halfred</v-toolbar-title>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat href="#solution">Solution</v-btn>
        <v-btn flat href="#about-us">Qui sommes nous</v-btn>
        <v-btn flat href="#contact-us">Contact</v-btn>
        <v-btn flat>Mon suivi</v-btn>
        <v-btn flat>Mes activités</v-btn>
        <v-btn flat>Mes alertes</v-btn>
      </v-toolbar-items>
      <v-spacer></v-spacer>
      <v-btn flat>Se Connecter</v-btn>
    </v-toolbar>
</template>

<script>
export default {
  name: 'navbar',
};
</script>

<style scoped>
  .toolbar__title {
    margin-right: 50px;
  }
</style>
