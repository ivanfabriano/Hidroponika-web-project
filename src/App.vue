<template>
  <v-app id="app">
    <nav-bar/>
    <router-view></router-view>
  </v-app>
</template>
<script>
import NavBar from "@/components/NavBar.vue"
export default {
  components:{
    NavBar,
  }
}
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200;300;400;600;700&display=swap");
#app {
  font-family: "Montserrat", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
