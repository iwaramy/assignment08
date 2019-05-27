<template>
  <div id="app">
    <Headers></Headers>
    <router-view></router-view>
    <Footers></Footers>
  </div>
</template>

<script>
    import Headers from './components/headers';
    import Footers from './components/footer';


    export default {
      name: 'app',
      components: {
        Headers,
        Footers,
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
