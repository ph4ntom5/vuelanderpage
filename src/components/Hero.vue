<template>
  <div class="container">
    <picture class="mx-auto">
      <img
        class="img-fluid mx-auto pt-5"
        src="../assets/illustration-intro.png"
        alt="two people organizing work illustrative scene"
      />
    </picture>
    <article>
      <h3 class="text-center mt-5 px-xl-15">
        All your files in one secure location, accessible anywhere.
      </h3>
      <p class="pt-2 px-xl-15">
        Fylo stores all your most important files in one secure location.Access
        them wherever you need,share and collaborate with friends, family and
        co-workers.
      </p>
    </article>
    <button class="mt-2">Get Started</button>
  </div> </template
>;

<script>
export default {
  name: "Hero",
  props: {
    msg: String,
  },
};
</script>

<style lang="scss" scoped>
button {
  background-color: #4fc4d4;
  border: none;
  border-radius: 2rem;
  color: white;
  padding: 0.7rem 4.5rem;
  font-size: 1rem;
  font-weight: 600;
}

button:hover {
  background-color: #62d2e1;
}

div {
  color: white;
  text-align: center;
}

h3 {
  font-weight: 700;
}

div.container {
  margin-top: 1rem;
}

article p {
  font-size: 1.2rem;
  opacity: 0.9;
}
</style>
