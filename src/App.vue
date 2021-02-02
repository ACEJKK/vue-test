<template>
  <div id="app">
    <img alt="My logo" src="./assets/我的网络头像.jpeg">
    <!--<HelloWorld msg="Welcome to My Websites"/>-->
    <information msg="Welcome to my Websites"/>
  </div>
</template>





<script>
import information from './components/information.vue'

export default {
  name: 'App',
  components: {
    information
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
