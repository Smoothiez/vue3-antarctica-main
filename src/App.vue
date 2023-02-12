<template>
  <!--<nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view/>
</template>

<script>
export default {
  name: 'App',
  components: {  }, 
 /*  data() {
    return {
    }
  }, */
  methods: 
  {
  }
}
</script>

<style scoped>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

/* Footer
Book Icon 
Masonry*/

nav a.router-link-exact-active {
  color: #42b983;
}
</style>


