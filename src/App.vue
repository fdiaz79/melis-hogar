<template>
  <div id="app">
    <app-header></app-header>

    
    <router-view/>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import header from './components/header';
  import footer from './components/footer';
  export default {
    components: {
      'app-header': header,
      'app-footer': footer
    }
    
  }
</script>

<style lang="scss">
#app {
  font-family: 'PT Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}


</style>
