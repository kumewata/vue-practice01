<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <header>
      <h1 class="site-title"><router-link to="/">becolomochi's portfolio</router-link></h1>
    </header>
    <hnav></hnav>
    <router-view/>
  </div>
</template>

<script>
import HeaderNav from '@/components/parts/NavHeader'
export default {
  name: 'App',
  components: {
    hnav: HeaderNav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
