<template>
  <div id="app">
  <!-- header -->
    <Header/>
  <!--  main -->
    <Main/>
  <!-- Footer -->
  <Footer/>
    
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Main from '@/components/Main.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header: Header,
    Main:Main,
    Footer:Footer,
  }
}
</script>

<style lang="scss">
@import'@/styles/general.scss';
</style>
