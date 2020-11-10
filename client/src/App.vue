<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      
    </v-app-bar>

    <v-main>
      <RequestForm/>
    </v-main>
  </v-app>
</template>

<script>
import RequestForm from './components/RequestForm';

export default {
  name: 'App',

  components: {
    RequestForm,
  },

  data: () => ({
    //
  }),
};
</script>
