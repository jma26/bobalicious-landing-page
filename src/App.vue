<template>
  <div class="App">
    <Navbar />
    <Home />
  </div>
</template>

<script>
import Home from '@/views/Home.vue';
import Navbar from '@/components/Navbar.vue';

export default {
  components: {
    Home,
    Navbar
  }
}
</script>


<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
  font-size: 100%;
  vertical-align: baseline;
}
</style>
