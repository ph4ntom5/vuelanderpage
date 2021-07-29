<template>
  <section class="mx-auto">
    <img
      class="img-fluid pt-1 mx-auto"
      src="../assets/illustration-stay-productive.png"
      alt="3 people working"
    />
    <article class="works-section">
      <h5 class=" mt-5 text-left">Stay productive, wherever you are</h5>
      <p class="pt-2 works-par">
        Never let location be an issue when accessing your files.Fylo has you
        covered for all of your file storage needs. <br />Securely share files
        and folders with friends, family and colleagues for live
        collaborations.No email attachments required.
      </p>
      <a class="link-fylo" href="#">See how Fylo works</a>
    </article>
  </section>
</template>

<script>
export default {
  name: "Works",
};
</script>

<style lang="scss" scoped>
section img {
  margin: 0 auto;
}
.works-section {
  text-align: left;
  margin-left: 2rem;
  margin-bottom: 12rem;
  h5 {
    font-weight: 600;
  }
  h5,
  p {
    color: white;
  }
  @media screen and (min-width: 768px) {
    .works-section h5 {
      text-align: center;
      margin-top: 100px;
    }
  }
}

.works-par {
  text-align: left;
}

.link-fylo {
  padding-right: 5rem;
  background: url(../assets/icon-arrow.svg) no-repeat right;
  background-position: 140px 3px;
  color: #4fc4d4;
  font-size: 0.9em;
  text-underline-offset: 7px;
}

.link-fylo:hover {
  color: white !important;
}

.link-fylo:hover img {
  background: white;
}
</style>
