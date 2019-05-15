<template>
  <div id="app">
    <AppContainer></AppContainer>
  </div>
</template>

<script>
import AppContainer from '@/components/AppContainer.vue';

export default {
  name: 'app',
  components: {
    AppContainer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  display: flex;
  flex-direction: column;
}
</style>
