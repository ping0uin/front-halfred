<template>
  <div>
    <v-layout
      column
      wrap
      class="my-5"
      align-center
    >
      <v-flex xs12 sm4 class="my-3">
        <v-card-title primary-title class="layout justify-center">
          <div id="contact-us" class="headline">Contact</div>
        </v-card-title>
        <v-card-text class="text-center">
          N'hésitez pas à nous contacter pour toute question ou information.
          <br/>
          Nous mettrons tout en oeuvre pour vous répondre dans les meilleurs
          délais.
        </v-card-text>
        <v-list class="transparent">
          <v-list-tile>
            <v-list-tile-action>
              <v-icon class="blue--text text--lighten-2">place</v-icon>
            </v-list-tile-action>
            <v-list-tile-content>
              <v-list-tile-title>Lille, France</v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
          <v-list-tile>
            <v-list-tile-action>
              <v-icon class="blue--text text--lighten-2">email</v-icon>
            </v-list-tile-action>
            <v-list-tile-content>
              <v-list-tile-title>my.halfred@gmail.com</v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
          <v-list-tile>
            <v-list-tile-action>
              <v-icon>fas fa-twitter</v-icon>
            </v-list-tile-action>
            <v-list-tile-content>
              <v-list-tile-title>twitter</v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
        </v-list>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
export default {
  name: 'contact-us',
};
</script>

<style scoped>

</style>
