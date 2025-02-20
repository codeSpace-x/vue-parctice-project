<template>
  <div id="app">
    <calendar></calendar>
    <home></home>
<!--    <router-link></router-link>-->
<!--    <router-view></router-view>-->
  </div>
</template>

<script>
import calendar from './components/calendar.vue'
import home from './views/home.vue'

export default {
  name: 'app',
  components: {
    calendar,
    home
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
