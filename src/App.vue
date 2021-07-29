<template>
  <Navigation />
  <Hero />
  <Features />
  <Works />
  <Testimonials />
  <Access />
  <Footer />
</template>

<script>
import Hero from "./components/Hero.vue";
import Features from "./components/Features.vue";
import Works from "./components/Works.vue";
import Testimonials from "./components/Testimonials.vue";
import Access from "./components/Access.vue";
import Footer from "./components/Footer.vue";
import Navigation from "./components/Navigation.vue";
export default {
  name: "App",
  components: {
    Navigation,
    Hero,
    Features,
    Works,
    Testimonials,
    Access,
    Footer,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap");

#app {
  $body-bg: #1c2230;
  $nav-link: #ebebeb;
  $secondary: white;
  $accent: #4fc4d4;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: $body-bg;
  background: #0c1524;
  font-family: "Open Sans", sans-serif;
}

html,
body {
  background-color: #1c2230;
}
</style>
