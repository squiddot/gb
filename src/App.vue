<template>
  <div id="app">
    <Nav></Nav>
    <Banner></Banner>
    <LinkCards></LinkCards>
  </div>
</template>

<script>
import Nav from "@/components/Nav";
import Banner from "@/components/Banner";
import LinkCards from "@/components/LinkCards";


export default {
  name: 'App',
  components: {
    Banner,
    LinkCards,
    Nav
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
