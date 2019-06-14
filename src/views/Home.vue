<template>
  <div class="Home">
    <div class="container">
      <div class="row">
        <div class="col-12 Home__company-name-column">
          <h1 class="Home__company-name text-center">Bobalicious</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-12 Home__call-to-action-column">
          <h1 class="d-block d-md-none Home__call-to-action">Open Source ordering system for small tea businesses</h1>
          <h1 class="d-none d-md-block Home__call-to-content">Boost online sales and reduce wait with Bobalicious</h1>
          <h5 class="d-none d-md-block Home__call-to-subcontent">The first open source and secure ordering system for small tea businesses</h5>
          <b-form class="Home__form">
            <b-form-input class="Home__input--email" placeholder="Enter your email address"></b-form-input>
            <b-button class="Home__submit-btn" type="submit">SIGN UP FOR BETA</b-button>
          </b-form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {
  },
};
</script>

<style lang="scss" scoped>
  .Home {
    background-image: linear-gradient(
      rgba(0, 0, 0, 0.3),
      rgba(0, 0, 0, 0.3)),
      url('../assets/background-tea.jpg');
    background-size: cover;
    display: flex;
    align-items: center;
    height: 100vh;
  }

  .Home__call-to-action, .Home__coming-soon-title, .Home__company-name, .Home__call-to-content, .Home__call-to-subcontent {
    color: $text-color;
    text-align: center;
  }

  .Home__company-name {
    font-weight: $bold;
    letter-spacing: 1.4px;
  }

  .Home__call-to-action {
    letter-spacing: 1.16px;
    text-align: center;
    font-weight: $normal;
  }

  .Home__call-to-subcontent {
    font-weight: $normal;
  }

  // Form
  .Home__input--email, .Home__submit-btn {
    width: 100%;
    display: block;
  }

  .Home__input--email {
    margin-top: 24px;
    font-weight: $medium;
  }

  .Home__submit-btn {
    font-weight: $medium;
    letter-spacing: 0.88px;
    margin-top: 8px;
    width: 100%;
  }

  @include desktop {
    .Home__input--email, .Home__submit-btn {
      max-width: 50%;
      margin-left: auto;
      margin-right: auto;
    }
  }

</style>
