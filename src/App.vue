<template>
  <v-app>
    <AppTopBar/>
    <router-view/>
  </v-app>
</template>

<script>
import AppTopBar from './components/shared/AppTopBar'

export default {
  name: 'App',

  components: {
    AppTopBar
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.link-home {
  color: white !important;
  text-decoration: none;
}
</style>
