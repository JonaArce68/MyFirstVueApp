<template>
  <div id="app">
    <div class="navbar-container">
      <div class="navbar-content">
        <router-link to="/home"><i class='bx bx-home-alt bx-sm'></i></router-link>
        <router-link to="/cesta"><i class='bx bx-package bx-sm'></i></router-link>
        <router-link to ="/deseos"><i class='bx bx-heart bx-sm' ></i></router-link>
        <router-link to ="/historial"><i class='bx bx-time-five bx-sm' ></i></router-link>
        </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="less">
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@100&display=swap');

.navbar-container{
  width: 100%;
  position: fixed;
  bottom: 0;
  .navbar-content{
    display: flex;
    padding: 20px;
    justify-content: space-between;
  a{
  color: rgb(68, 68, 68);
  &.router-link-exact-active {
  color: rgb(172, 11, 92);
}
    }

  }
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
*{
  font-family: 'Josefin Sans', sans-serif;
  margin: 0px;
  padding: 0px;
}

</style>
