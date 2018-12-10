<template>
  <v-app id="app">
    <router-view/>
    <Feeter></Feeter>
  </v-app>
</template>

<script>
import Feeter from '@/components/Feeter';

export default {
  name: 'App',
  components: {
    Feeter,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
