<template>
  <div id="app">
    <!-- header -->
    <Header/>
    
  </div>
</template>

<script>
import Header from '@/components/Header.vue';

export default {
  name: 'App',
  components: {
    Header: Header
  }
}
</script>

<style lang="scss">
  #app{
    font-family: 'Roboto', sans-serif;
  }
</style>
