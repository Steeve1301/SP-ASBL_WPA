<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand text-white font-weight-bold" href="#">Solidarités Plurielles</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active text-white" aria-current="page" href="#">Accueil</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Présentation</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Services</a>
          </li>
        </ul>
      </div>
      </div>
    </nav>
    <header>
      
    </header>
    <home/>
  </div>
</template>

<script>
import home from './components/home.vue'

export default {
  name: 'App',
  components: {
    home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c2b2b;
  
}
header{
  height:40vh;
  background-image: url("../src/assets/social.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: bottom;
}
</style>
