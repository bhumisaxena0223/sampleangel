<template>
  <div id="mainheader">
    sss
    <b-navbar toggleable="md" type="light" variant="light" sticky>
      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
      <b-navbar-brand href="#" stlye="padding-top: 0rem; padding-bottom: 0rem;">
        <span style="vertical-align: -webkit-baseline-middle;">Sample Header</span>
      </b-navbar-brand>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'mainheader',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
