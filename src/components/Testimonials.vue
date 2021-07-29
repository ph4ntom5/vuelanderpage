<template>
  <img class="quotes" src="../assets/bg-quotes.png" />

  <div class="card-body testi text-left m-5">
    <p class="testi-card-text mt-4 text-sm-left">
      Fylo has improved our team productivity by an order of magnitude.Since
      making the switch our team has become a well-oiled collaboration machine.
    </p>
    <div class=" card-img-top container text-left">
      <div class="row avatar">
        <div class="avatar-img">
          <img
            class="img-fluid"
            src="../assets/profile-1.jpg"
            alt="Card image cap"
          />
          <div class="row testi-caption">
            <h5 class="card-title">Satish Patel</h5>

            <caption>
              Founder & CEO, Huddle
            </caption>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Second Tesitmonial-->

  <div class="card-body testi text-left m-5">
    <p class="testi-card-text mt-4 text-sm-left">
      Fylo has improved our team productivity by an order of magnitude.Since
      making the switch our team has become a well-oiled collaboration machine.
    </p>
    <div class=" card-img-top container text-left">
      <div class="row avatar">
        <div class="avatar-img">
          <img
            class="img-fluid"
            src="../assets/profile-2.jpg"
            alt="Card image cap"
          />
          <div class="row testi-caption">
            <h5 class="card-title">Bruce McKenzie</h5>

            <caption>
              Founder & CEO, Huddle
            </caption>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Third Tesitmonial-->

  <div class="card-body testi text-left m-5">
    <p class="testi-card-text mt-4 text-sm-left">
      Fylo has improved our team productivity by an order of magnitude.Since
      making the switch our team has become a well-oiled collaboration machine.
    </p>
    <div class=" card-img-top container text-left">
      <div class="row avatar">
        <div class="avatar-img">
          <img
            class="img-fluid"
            src="../assets/profile-3.jpg"
            alt="Card image cap"
          />
          <div class="row testi-caption">
            <h5 class="card-title">Iva Boyd</h5>

            <caption>
              Founder & CEO, Huddle
            </caption>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Testimonials",
};
</script>

<style lang="scss" scoped>
.quotes {
  position: relative;
  top: 3rem;
  left: 3rem;
  width: 1.5rem;
}

.testi {
  background-color: #212a3d;
  border-radius: 12px;
  margin-bottom: 2rem;

  .testi-card-text {
    color: white;
    text-align: left;
    opacity: 0.8;
  }
}

.card-title {
  color: white;
  margin-left: 5rem !important;
}

.card-img-top img {
  margin-top: 1rem;
  margin-left: -0.5rem;
  border-radius: 100rem;
  width: 12%;
}
.avatar {
  display: flex;
  align-items: center;
  justify-content: center;
}
.testi-caption {
  margin-top: -3rem;
  margin-left: -2.5rem;
  h5 {
    font-size: 1rem;
    font-weight: 600;
  }
  caption {
    font-size: 0.8rem;
    color: white;
    margin-top: -0.5rem;
    margin-left: 5rem;
  }
}
</style>
