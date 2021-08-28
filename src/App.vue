<template>
  <div id="app">
    <div class="frame">
      <div id="nav">
        <router-link to="/shop">Shop</router-link>
      </div>
      <router-view/>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  background-color: rgb(235, 235, 235);
  height: 100vh;
  display: flex;
  justify-content: center;
}

.frame {
  width: 60%;
  height: 100vh;
  background-color: rgb(168, 168, 231);
}

#nav {

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
