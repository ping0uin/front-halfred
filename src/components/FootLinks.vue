<template>
    <div>
      <v-footer class="blue darken-2">
        <v-layout row align-center>
          <v-flex xs12>
            <div class="white--text ml-3">
              <v-icon class="red--text">favorite</v-icon>
              <a class="white--text" href="" target="_blank">Politique de confidentialité</a>
              <a class="white--text" href="">Conditions d'utilisation</a>
              <a class="white--text" href="">Rappel et information de sécurité</a>
              <a class="white--text" href="">Consentement relatif aux cookies</a>
            </div>
          </v-flex>
        </v-layout>
      </v-footer>
    </div>
</template>

<script>
export default {
  name: 'foot-links',
};
</script>

<style scoped>
.white--text {
  padding-right: 20px;
}
</style>
