<template>
  <NavBarComp/>
  <router-view />
  <FooterComp/>
</template>

<script>
import NavBarComp from './components/NavBar-comp.vue';
import FooterComp from './components/Footer-comp.vue'
export default {
  components: {
    NavBarComp,
    FooterComp
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");

#app {
  font-family: "Lobster", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #EEEBDD;
  background-color: #1B1717;
}

::-webkit-scrollbar {
  display: none;
}

/* nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #EEEBDD;
  text-decoration: none;
  
} */

nav a.router-link-exact-active {
  border-bottom: 2px solid #CE1212;
}
</style>
