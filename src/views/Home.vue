<template>
  <div class="Home">
    <div class="container">
      <div class="row">
        <div class="col-12 Home__coming-soon-column">
          <h2 class="Home__coming-soon-title">Coming Soon...</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-12 Home__call-to-action-column">
          <h1 class="Home__call-to-action">Order bubble tea with ease!</h1>
          <p class="Home__call-to-content">Waiting in long queues has never been easier! Order through this app and pick up your drink on arrival!</p>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-md-4">
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
        <div class="col-12 col-md-4">
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
        <div class="col-12 col-md-4">
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
// @ is an alias to /src

export default {
  name: 'home',
  components: {
  },
};
</script>

<style lang="scss" scoped>
  .Home__coming-soon-title {
    margin-top: 88px;
  }
// > MD devices
  .Home__call-to-action-column {
    margin-top: 48px;
  }

</style>
