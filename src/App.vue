<template>
  <div id="app">
    <welcome/>
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
  import welcome from './components/common/welcome.vue'
  export default {
    name: 'app',
    components:{
      welcome
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
  margin-top: 60px;
}
</style>
