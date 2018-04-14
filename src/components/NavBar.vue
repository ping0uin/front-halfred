<template>
    <v-toolbar>
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title id="mainTitle">Halfred</v-toolbar-title>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat>Link One</v-btn>
        <v-btn flat>Link Two</v-btn>
        <v-btn flat>Link Three</v-btn>
        <v-btn flat>Link Four</v-btn>
        <v-btn flat>Link Five</v-btn>
        <v-btn flat>Link Six</v-btn>
      </v-toolbar-items>
      <v-spacer></v-spacer>
      <v-btn flat>Link Seven</v-btn>
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
