<template>
  <nav>
    <router-link :to="{ name: 'Home' }">Home</router-link>
    <router-link :to="{ name: 'AddProject' }">Add Project</router-link>
  </nav>
  <router-view />
</template>

<style>
body {
  background: #d3d3d3;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 600px;
  margin: 0 auto;
  color: #2c3e50;
}
</style>
