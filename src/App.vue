<template>
  <Home/>
  
  <h1>Data Binding in vue js</h1>
  <Data_binding />
  
</template>

<script>
import Home from './components/Home'
import Data_binding from './components/Data_binding'
export default {
  name: 'App',
  components: {
    Home,
    Data_binding
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
