<template>
  <div id="app">
    <header id="nav" class="header_app">
      <router-link to="/">Главная</router-link>
    </header>

    <router-view/>

  </div>
</template>



<style lang="scss">


#nav {

  a {
    font-size: 1.6rem;
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
