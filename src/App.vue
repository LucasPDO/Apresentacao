<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">Contato</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  padding: 0;
  margin: 0;
  box-shadow: border-box;
}
nav {
  padding: 30px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 50px;
}
nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
