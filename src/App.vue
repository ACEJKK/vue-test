<template>
  <div id="app">
    <img alt="My logo" src="./assets/我的网络头像.jpeg">
    <Information msg="Welcome to my Websites"/>
    <HelloWorld msg="Welcome to My Websites"/>
  </div>
</template>





<script>
import Information from './components/Information'
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    Information,
    HelloWorld
  }
}
</script>




<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
