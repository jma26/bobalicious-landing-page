<template>
  <div class="Navbar">
    <b-navbar toggleable="sm" type="dark" variant="info" fixed="top">
      <div class="container">
      <b-navbar-brand href="#">NavBar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item class="mr-5" href="#">About</b-nav-item>
          <b-nav-item class="mr-5" href="#">Explore</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>

<script>

export default {
  name: 'Navbar'
};
</script>

<style lang="scss" scoped>
@media only screen and (max-width: 992px) {
  .Navbar .navbar .container {
    max-width: 100%;
  }
}
</style>
