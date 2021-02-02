<template>
  <div>
    <div id="app">
      <img alt="My logo" src="./assets/我的网络头像.jpeg">
      <Information msg="Welcome to my Websites"/>
      <!-- <HelloWorld msg="Welcome to My Websites"/> -->
    </div>
    <div id="Feiming">
      <h1>Today is a good day</h1>
      <h1>Today is a good day</h1>
    </div>
  </div>
</template>





<script>
import Information from './components/Information'
// import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    Information,
    
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
  border: 1px solid red;
}

#Feiming {
  border: 1px blue solid;
  color: gray;
  width: 400px;
  height: 400px;
  margin: 200px auto;
  padding: 200px;
  
}
</style>
