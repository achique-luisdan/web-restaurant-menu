<template>
  <ContainerPlates msg="Welcome to Your Vue.js App"/>
</template>

<script>

import ContainerPlates from './components/ContainerPlates.vue';

export default {
  name: 'App',
  components: {
    ContainerPlates
  }
}
</script>

<style>
  @import './assets/css/normalize.css';
  @import './assets/css/skeleton.css';
  body {
    background-color: #363533ff; 
  }
</style>
