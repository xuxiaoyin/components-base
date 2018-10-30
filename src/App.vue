<template>
  <div id="app">
    <v-home></v-home>
    <v-news></v-news>
    <v-life></v-life>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import News from './components/News.vue'
import Life from './components/Lify.vue'

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      flg:true
    }
  },
  components:{
  	'v-home':Home,
  	'v-news':News,
  	'v-life':Life
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

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
