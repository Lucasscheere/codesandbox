<template>
  <div id="app">
    <Header />
    <Carousel />
    <LastNews />
    <BackToTop />
    <Footer />
  </div>
</template>

<script>
//Tentando fazer o desafio do link https://github.com/FolhaSP/teste-para-frontend/blob/master/layouts/extra_small-mobile.png
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import Carousel from "./components/Carousel.vue";
import LastNews from "./components/LastNews.vue";
import BackToTop from "./components/BackToTop.vue";

export default {
  name: "App",
  components: { Header, Footer, Carousel, LastNews, BackToTop},
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 100%;
  font-family: Helvetica, sans-serif;
}
</style>
