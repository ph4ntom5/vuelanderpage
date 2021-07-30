<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-dark pt-4">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"
          ><img
            src="../assets/logo.svg"
            alt=""
            width="30"
            height="24"
            class="d-inline-block align-text-top"
        /></a>

        <div class="navbar navbar-expand-sm" id="navbarNav">
          <ul class="navbar-nav flex-row">
            <li class="nav-item">
              <a class="nav-link" href="#">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Team</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Sign In</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navigation",
};
</script>

<style lang="scss" scoped>
.navbar-brand img {
  width: 6rem;
}
.navbar-collapse {
  justify-content: flex-end;
  width: 40%;
  .navbar-nav .nav-link {
    color: #ebebeb;
  }
}
.nav-link a {
  padding: 2rem !important;
}
</style>
