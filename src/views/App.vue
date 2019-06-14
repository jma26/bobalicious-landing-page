<template>
  <div class="App">
    <!-- <Navbar /> -->
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
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
  // Relative font-sizing for mobile devices
  body {
    font-size: 12px !important;
    margin: 0;
    padding: 0;
  }
  h1 {
    font-size: 240% !important;
  }
  h2 {
    font-size: 220% !important;
  }
  h3 {
    font-size: 200% !important;
  }
  h4 {
    font-size: 180% !important;
  }
  h5 {
    font-size: 160% !important;
  }
  h6 {
    font-size: 140% !important;
  }
  p {
    font-size: 120% !important;
  }
</style>
