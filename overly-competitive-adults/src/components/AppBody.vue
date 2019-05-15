<template>
  <div class="app-body">
    <AppLeftSideBar class="app-side-bar"></AppLeftSideBar>
    <AppMain class="app-main"></AppMain>
  </div>
</template>

<script>
import AppLeftSideBar from '@/components/AppLeftSideBar.vue'
import AppMain from '@/components/AppMain.vue'

export default {
  name: 'AppBody',
  components: {
    AppLeftSideBar,
    AppMain
  }
}
</script>

<style>

.app-body {
  flex: 1;
  display: flex;
}

.app-side-bar {
  width: 20%;
  min-width: 100px;
  order: 1;
}

.app-main {
  flex: 1;
  order: 2;
}

</style>
