<template>
  <div class="container">
    <div class="row mt-5">
      <div class="card mx-auto" style="width: 18rem">
        <img
          class="card-img-top img-fluid"
          src="../assets/icon-access-anywhere.svg"
          alt="Card image cap"
        />
        <div class="card-body">
          <h5 class="card-title">Access your files, anywhere</h5>
          <p class="card-text">
            The ability to use a smartphone, tablet or computer to access your
            account means your files follow you everywhere.
          </p>
        </div>
      </div>
      <div class="card mx-auto" style="width: 18rem">
        <img
          class="card-img-top img-fluid security"
          src="../assets/icon-security.svg"
          alt="Card image cap"
        />
        <div class="card-body">
          <h5 class="card-title">Security you can trust</h5>
          <p class="card-text">
            2-factor authentication and user-controlled encryption are just a
            couple of the security features we allow to help secure your files.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="card mx-auto" style="width: 18rem">
          <img
            class="card-img-top img-fluid"
            src="../assets/icon-collaboration.svg"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Real-time collaboration</h5>
            <p class="card-text">
              Securely share files and folders with friends,family and
              colleagues for live collaboration.No email attachments required.
            </p>
          </div>
        </div>
        <div class="card mx-auto" style="width: 18rem">
          <img
            class="card-img-top img-fluid"
            src="../assets/icon-any-file.svg"
            alt="Card image cap"
          />
          <div class="card-body last-card">
            <h5 class="card-title">Store any type of file</h5>
            <p class="card-text">
              Whether you're sharing holidays photos or work documents. Fylo has
              you covered allowing for all file types to be securely stored and
              shared.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
};
</script>

<style lang="scss" scoped>
.card {
  margin-top: 6rem;
  padding: 0;
  text-align: center;
  border: none;
  background: transparent;

  img {
    width: 23%;
    margin: 0 auto;
  }

  .security {
    width: 20%;
  }
}
.card-body {
  h5 {
    margin-top: 1rem;
    font-weight: 600;
  }

  h5,
  p {
    color: white;
  }
  .card-text {
    opacity: 0.8;
  }
}

.last-card {
  margin-bottom: 7rem;
}
</style>
