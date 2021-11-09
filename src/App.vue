<template>
  <div id="app">
    <div class="top">
      <Nav></Nav>
      <Banner></Banner>
    </div>
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

<style >
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&family=Saira+Condensed:wght@700;900&display=swap');
</style>
