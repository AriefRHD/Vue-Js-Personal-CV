<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->
    

    <div class="wrapper">
      <HelloWorld msg=" CV Arief Rahman Hidayat" />

      <nav>
        <RouterLink to="/">Profil Lengkap</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />

  <div class="card-footer text-muted">
      <footer>Copyright 2022@arief</footer>
      <a href=""><i class="emot fa-brands fa-instagram"></i></a>
      <a href=""><i class="emot fa-brands fa-github"></i></a>
      <a href=""><i class="emot fa-solid fa-envelope"></i></a>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }

  .card-footer{
    text-align: center;
    /* background-color: rgb(172, 62, 62); */ 
    color: white;
    height: 30px;
    transform: translate(300px, 90px);
    font-size: 20px;
  }

  .emot{
    margin-left: 10px;
  }
}
</style>
