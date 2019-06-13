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
          <h1 class="Home__call-to-action">Open Source ordering system for small tea businesses</h1>
          <b-form>
            <b-form-input class="Home__input--email" placeholder="Enter your email address"></b-form-input>
            <b-button class="Home__submit-btn" type="submit">SIGN UP FOR BETA</b-button>
          </b-form>
          <p class="d-sm-block d-none Home__call-to-content">Waiting in long queues has never been easier! Order through this app and pick up your drink on arrival!</p>
        </div>
      </div>
      <div class="row d-sm-block d-none">
        <div class="col-sm-4">
            <b-card
              title="Fast pick up"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>Skip the lines and pick up on arrival</b-card-text>

              <b-button href="#" variant="primary">Go somewhere</b-button>
            </b-card>
        </div>
        <div class="col-sm-4">
          <div>
          <b-card
            title="Free to use"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
          >
            <b-card-text>For local tea businesses by developers who love boba</b-card-text>

            <b-button href="#" variant="primary">Go somewhere</b-button>
          </b-card>
          </div>
        </div>
        <div class="col-sm-4">
          <b-card
            title="Safe, secure payment"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
          >
            <b-card-text>Secured with Stripe, the best software platform for handling online payments</b-card-text>

            <b-button href="#" variant="primary">Go somewhere</b-button>
          </b-card>
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

  .Home__call-to-action, .Home__coming-soon-title, .Home__company-name {
    color: #FFF;
  }

  .Home__call-to-action {
    letter-spacing: 1.16px;
    text-align: center;
    font-weight: 400;
  }

  .Home__company-name {
    font-weight: 700;
    letter-spacing: 1.4px;
  }

  .Home__input--email {
    margin-top: 24px;
    font-weight: 500;
  }

  .Home__submit-btn {
    font-weight: 500;
    letter-spacing: 0.88px;
    margin-top: 8px;
    width: 100%;
  }

</style>
