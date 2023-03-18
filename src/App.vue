<template>
  <div id="apps">
    <router-view />
    <CounterPage />
  </div>
</template>

<script>
import CounterPage from './components/CounterPage.vue'
export default {
  name: 'App',
  components: {
    CounterPage,
  }
}
</script>

<style>
html {
  height: 100vh;
  display: grid;
  align-content: center;
  justify-content: center;
}

body {
 background: rgb(2,0,36);
 background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(0,212,255,1) 100%);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(8, 1, 41);
  border-radius: 35px;
  width: 100%;
  height: 20em;
  padding: 22px 0 5px 0;
}

h1,
h3 {
  color: white;
}</style>