<template>
  <div id="app">
    <Donghua/>
  </div>
</template>

<script>
  import Donghua from './components/Donghua.vue'
  export default {
    name: 'App',
    components: {
      Donghua
    }
  }
</script>

<style>
  #app {
    margin: 0px;
    padding: 0px;
  }
  body{
    margin: 0px;
    padding: 0px;
    overflow: hidden;
    position: fixed;
    top: 0px;
    left: 0px;
    font-size: 12px;
  }
</style>
