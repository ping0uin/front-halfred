<template>
  <div>
    <v-parallax :src="require('@/assets/test.jpeg')" height="600">
      <v-layout
        column
        align-center
        justify-center
        class="white--text"
      >
        <img src="@/assets/vuetify.png" alt="Vuetify.js" height="200">
        <h1 class="white--text mb-2 display-1 text-xs-center">Maîtrisez vos capacités</h1>
        <div class="subheading mb-3 text-xs-center">Trouvez votre ryhtme</div>
        <v-btn
          class="blue lighten-2 mt-5"
          dark
          large
          href="/front-alfred"
        >
          Créez votre compte
        </v-btn>
      </v-layout>
    </v-parallax>
  </div>
</template>

<script>
export default {
  name: 'hangs-picture',
};
</script>

<style scoped>

</style>
