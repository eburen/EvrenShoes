<template>
  <div id="app">
    <NavBar />
    <router-view />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
export default{
  name: 'App',
  components:{
    NavBar,
  }
}
</script>
<style>
* {
  box-sizing: border-box;
  font-family: Arial;
}

#page-wrap {
  margin: auto;
  max-width: 800px;
  min-height: 100vh;
}

button {
  background-color: black;
  border: none;
  color: white;
  border-radius: 9px;
  cursor: pointer;
  font-size: 16px;
  padding: 16px;
  font-weight: bold;
  outline: 0;
}
</style>
