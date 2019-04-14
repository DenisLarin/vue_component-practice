<template>
  <div class="container">
    <div class="row">
      <Header></Header>
    </div>
    <hr>
    <div class="row">
      <Servers></Servers>
      <ServerDetail></ServerDetail>
    </div>
    <hr>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from "./Header";
  import Servers from "./Servers";
  import ServerDetail from "./ServerDetail";
  import Footer from "./Footer";
  export default {
    components: {Footer, ServerDetail, Servers, Header}
  }
</script>

<style>

</style>
