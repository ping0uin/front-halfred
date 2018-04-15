<template>
  <div>
    <v-parallax :src="require('@/assets/section.jpg')" height="380">
      <v-layout column align-center justify-center>
        <div class="headline white--text mb-3 text-xs-center">
          Ne soyez plus seul pour apprendre à connaître vos limites
        </div>
        <em>Adopter Halfred dès aujourd'hui</em>
        <v-btn
          class="blue lighten-2 mt-5"
          dark
          large
          href="/pre-made-themes"
        >
          Créez votre compte
        </v-btn>
      </v-layout>
    </v-parallax>
  </div>
</template>

<script>
export default {
  name: 'foot-picture',
};
</script>

<style scoped>

</style>
