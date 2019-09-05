<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome PHP Storm"/>
    <HelloWorldTest msg="Test branch PHP Storm"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorldTest from './components/HelloWorldTest.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    HelloWorldTest
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
