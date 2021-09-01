<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/seeker">Seek Projects 🌩</router-link>|
    <router-link to="/poster"> Post a Project 🧑‍💻</router-link>
  </div>
  <router-view />
</template>

<style lang="scss">
@import "~bulma/css/bulma.css";

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
