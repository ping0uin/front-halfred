<template>
  <div class="landing">
      <v-app light>
        <v-content>

          <section>
            <HangsPicture/>
          </section>

          <section>
            <ProblemPresentation/>
          </section>

          <section>
            <SolutionFundations/>
          </section>

          <section>
            <FootPicture/>
          </section>

          <section>
            <AboutUs/>
          </section>

          <section>
            <ContactUs/>
          </section>

        </v-content>
      </v-app>
  </div>
</template>

<script>
import HangsPicture from './HangsPicture';
import ProblemPresentation from './ProblemPresentation';
import SolutionFundations from './SolutionFundations';
import FootPicture from './FootPicture';
import AboutUs from './AboutUs';
import ContactUs from './ContactUs';

export default {
  name: 'landing',
  components: {
    HangsPicture,
    ProblemPresentation,
    SolutionFundations,
    FootPicture,
    AboutUs,
    ContactUs,
  },
  data() {
    return {
      title: 'Your Logo',
    };
  },
};
</script>

<style scoped>

</style>
