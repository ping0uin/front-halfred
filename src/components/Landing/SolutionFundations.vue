<template>
  <div>
    <v-layout
      column
      wrap
      class="my-5"
      align-center
    >
      <v-flex xs12 sm4 class="my-3">
        <div class="text-xs-center">
          <h2 id="solution" class="headline">Comment ça fonctionne ?</h2>
          <span class="subheading">
                Halfred repose sur 3 éléments
              </span>
        </div>
      </v-flex>
      <v-flex xs12>
        <v-container grid-list-xl>
          <v-layout row wrap align-top>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="blue--text text--lighten-2">watch</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">Un traqueur d'activité</div>
                </v-card-title>
                <v-card-text>
                  Le traqueur d'activité est le point de départ de notre solution.
                  Il nous permet de suivre votre activité quotidienne et d'enregistrer
                  le nombre de pas et la distance que vous parcourez tous les jours.
                  Que vous vous déplaciez à l'aide de dispositifs médicaux ou non,
                  il y a un forcément un traqueur pour vous.
                  <br/>
                  <a class="blue--text" href="">
                    Retouvez une liste de traqueurs compatibles ici.
                  </a>

                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="blue--text text--lighten-2">web</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">Une Application Web</div>
                </v-card-title>
                <v-card-text>
                  Sur cette application vous pouvez suivre votre activité quasiment
                  en temps réel. Vous pouvez également consulter votre historique,
                  enregistrer votre état et vos limites, mais surtout gérer vos alertes.
                  La gestion de vos alertes vous permettra dêtre prévenu quand vous le
                  souhaitez de l'approche de vos limites quotidiennes.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="blue--text text--lighten-2">chat</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">Un chatbot</div>
                </v-card-title>
                <v-card-text>
                  Ce chatbot est la personification d'Halfred.
                  Il est votre assistant personnel et à ce titre,
                  il vous permet de converser pour l'enregistrement de vos données,
                  demander des informations sur votre activité
                  et vous prévenir de l'approche de vos limites
                  selon les alertes que vous avez configuré dans votre compte.
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
export default {
  name: 'solution-fundations',
};
</script>

<style scoped>

</style>
