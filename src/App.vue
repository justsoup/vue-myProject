<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{msg}}</h1>
    <firstcomponent></firstcomponent>
    <router-view></router-view>
  </div>
</template>

<script>
import firstcomponent from './components/first'
export default {
  data () {
    return {
      msg: 'Hello world!'
    }
  },
  components: {firstcomponent}

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
