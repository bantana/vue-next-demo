<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/composition">Composition API</router-link> |
      <router-link to="/options">Options API</router-link> 
    </div>
    <router-view/>
  </div>
</template>

<style lang="less">
#app {
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-size: 16px;
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
