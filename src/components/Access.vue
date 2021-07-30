<template>
  <div class="container px-lg-12">
    <section class="wrapper ">
      <section>
        <h3 class="text-center mb-2">Get early access today</h3>
        <p>
          It only takes a minute to sign up and our free starter tier is
          extremely generous. If you have any questions, our support team would
          be happy to help you.
        </p>
      </section>
      <form>
        <div class="form-group mx-auto text-center d-lg-flex flex-row">
          <input
            type="email"
            class="form-control col-lg-0 px-lg-10"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
            placeholder="email@fylo.com"
          />
          <button
            type="submit"
            class="btn btn-primary mt-4 m-lg-0 col-lg-0 mx-lg-4"
          >
            Get Started For Free
          </button>
        </div>
      </form>
    </section>
  </div>
</template>

<script>
export default {
  name: "Access",
};
</script>

<style lang="scss" scoped>
.wrapper {
  margin-top: 14rem;
  padding-top: 1rem;
  padding-bottom: 3rem;
  background-color: #1c2330;
  margin-left: 2rem;
  margin-right: 2rem;
  border-radius: 1.2rem;
}
section h3 {
  margin-top: 3rem;
  color: white;
  font-weight: 600;
}

section p {
  color: white;
  text-align: center;
  padding: 1rem 2rem;
  font-size: 1.2rem;
}

.form-group {
  padding-left: 3rem;
  padding-right: 3rem;
}
.form-group input {
  height: 4rem;
  border-radius: 100rem;
  width: 95%;
  margin-top: 1rem;
  margin: 0 auto;
}
.form-group input[placeholder] {
  padding-left: 3rem;
}

form button {
  background-color: #4fc4d4;
  height: 4rem;
  width: 95%;
  border-radius: 100rem;
  font-weight: 600;
  font-size: 1.2rem;
}

form button:hover {
  background-color: #62d2e1;
}
</style>
