<template>
  <div id="app">
    <md-layout md-gutter>
      <md-layout md-flex="33">
        <search></search>
      </md-layout>
      <md-layout>
        <router-view></router-view>
      </md-layout>
    </md-layout>
  </div>
</template>

<script>
var search = require('./components/Search')

export default {
  name: 'app',
  components: {
    'search': search
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  margin-top: 60px;
}
</style>
