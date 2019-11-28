<template>
  <div id="app">
    <app-header></app-header>

    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
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

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
