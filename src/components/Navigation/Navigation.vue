<template>
    <h1>
        je suis une navigation
        <button v-if="isConnected" @click="Logout">Logout</button>
        <router-link to="/users">Users</router-link>
    </h1>
</template>


<script>
import { mapActions, mapGetters } from 'vuex';

export default {
  name: 'Navigation',
  data() {
    return {

    };
  },
  methods: {
    ...mapActions('auth', [
      'Logout',
    ]),
  },
  computed: {
    ...mapGetters('auth', [
      'isConnected',
    ]),
  },
};
</script>

<style scoped>

</style>
