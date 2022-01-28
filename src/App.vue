<template>
  <div id="app">

    <div class="container">
  <b-navbar toggleable="lg" type="dark" variant="">
    <b-navbar-brand href="#"><img src="./assets/imgs/logo.png" class="logo"></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav >
      <b-navbar-nav class="ms-auto">
        <b-nav-item href=""><router-link to="/">Home</router-link> |</b-nav-item>
        <b-nav-item href="" ><router-link to="/about">About</router-link></b-nav-item>
        <b-nav-item href="" ><router-link to="/contactus">Contact-us</router-link></b-nav-item>
        <b-nav-item href="" ><router-link to="/service">Service</router-link></b-nav-item>
        <b-nav-item href="" ><router-link to="/footer">Footer</router-link></b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        

        
        
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
    <div id="nav">
      
      
      
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
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

.logo{
  height:7vh;
}
</style>
