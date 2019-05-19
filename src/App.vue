<template>
  <div id="app">
    <b-container>
      <b-row>
        <b-col>
        <Header></Header>y
        <footer></footer>
        </b-col>
      </b-row>
    </b-container>
    <router-view/>
  </div>
</template>

<script>  
import footer from './components/footer';
import Header from './components/Header';
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size:18px;
}
</style>
