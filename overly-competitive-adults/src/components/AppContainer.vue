<template>
  <div class="app-container">
    <AppHeader></AppHeader>
    <AppBody></AppBody>
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue';
import AppBody from '@/components/AppBody.vue';

export default {
  name: 'AppContainer',
  components: {
    AppHeader,
    AppBody
  }
}
</script>

<style lang="less">
@import '../assets/vars.less';

.app-container {
  display: flex;
  flex-direction: column;
  flex: 1;
  background: @app-primary-color;
  font-family: @app-font-family;
  color: @app-font-color;
}
</style>
