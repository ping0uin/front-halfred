<template>
  <div>
    <v-container grid-list-xl>
      <v-layout row wrap justify-center class="my-5">
        <v-flex xs12 sm4>
          <v-card class="elevation-0 transparent">
            <v-card-title primary-title class="layout justify-center">
              <div class="headline">Combien ça coûte ?</div>
            </v-card-title>
            <v-card-text>
              Halfred est une solution Open Source, totalement gratuite
              dans son utilisation standard. Cette initiative est née d'une
              situation personnelle qui devant le handicap nous a mis face
              à un constat : rien ni personne ne vous aidera à trouver votre
              rythme. La seule personne capable de vous y aider, c'est vous même.
              Ayant trouvé une solution satisfaisante, nous avons décidé de
              la mettre à disposition de tous.
              Notre volonté est simplement de pouvoir aider le maximum de personne
              à trouver ou retrouver un ryhtme de vie
              en harmonie avec ses possibilités.
              <p/>
              Si vous êtes un professionnel et que vous souhaitez ouvrir cette
              solution à un ensemble de patients, nous avons des solutions
              professionnelles adaptées qui vous offrirons en plus des
              suivis de groupe, et des fonctionnalités adaptées à un usage
              pro.
              <a class="blue--text" href="">
                Contactez-nous
              </a> pour plus d'informations.
            </v-card-text>
          </v-card>
        </v-flex>

        <v-flex xs12 sm4 offset-sm1>
          <v-card class="elevation-0 transparent">
            <v-card-title primary-title class="layout justify-center">
              <div id="about-us" class="headline">Qui sommes nous ?</div>
            </v-card-title>

            <v-layout>
                <v-card class="contactCard">
                  <v-card-media
                    :src="require('@/assets/mla.png')"
                    height="250px"
                  >
                  </v-card-media>
                  <v-card-title primary-title>
                    <div>
                      <div class="headline">Marc</div>
                      <span class="grey--text">
                        Eternel optimiste, il voit toujours le
                        meilleur dans toutes les situations.
                        Son plus grand bonheur c'est celui des
                        autres.
                      </span>
                    </div>
                  </v-card-title>
                </v-card>

                <v-card>
                  <v-card-media
                    :src="require('@/assets/denouche.jpg')"
                    height="250px"
                  >
                  </v-card-media>
                  <v-card-title primary-title>
                    <div>
                      <div class="headline">Antoine</div>
                      <span class="grey--text">
                        Toujours de bonne humeur, il est de
                        nature curieuse et il adore les défi.
                        Particuilèrement doué, il les relève
                        avec brio.
                      </span>
                    </div>
                  </v-card-title>
                </v-card>
            </v-layout>

          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>


export default {
  name: 'about-us',
  data: () => ({
    show: false,
  }),
};
</script>

<style scoped>
.contactCard {
  margin-right: 10px;
}
</style>
