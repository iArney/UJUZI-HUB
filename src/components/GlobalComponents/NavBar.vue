<template>
  <div>
    <nav class="navbar shadow-sm bg-white sticky-top">
      <div class="container-fluid mx-auto" style="height: 50px">
        <div class="row justify-content-center position-relative mx-auto w-100">
          <div class="px-5 col-4 col-md-2 col-sm-1 mx-5">
            <img
              class="img-logo"
              style="height: 170px; width: 170px; margin-top: -3.75rem"
              src="@/assets/ujuziHubOfficialLogo.webp"
              alt="logo"
            />
          </div>
          <div class="navbar-nav col-4 mt-2 col-md-4 col-sm-1 col-xs-1">
            <ul class="nav mx-auto d-none d-sm-none d-md-none d-lg-flex">
              <li class="nav-item">
                <a class="nav-link active fw-bold" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="color: #f18626" href="#">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="color: #f18626" href="#">Online</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="color: #f18626" href="#"
                  >Contact Us</a
                >
              </li>
            </ul>
          </div>
          <div class="col-2">
            <div
              class="btn bg-info rounded-pill mt-2 w-50 d-none d-sm-none d-md-none d-lg-flex mx-auto"
            >
              <span class="mx-auto">login</span>
            </div>
            <div class="col">
              <a
                class="link-b btn btn-primary w-25 h-25 m-auto d-md-flex d-lg-none d-xl-none"
                data-bs-toggle="offcanvas"
                href="#offcanvasExample"
                role="button"
                aria-controls="offcanvasExample"
              >
                <span class="m-auto">MENU</span>
              </a>
              <div
                class="offcanvas offcanvas-start"
                tabindex="-1"
                id="offcanvasExample"
                aria-labelledby="offcanvasExampleLabel"
              >
                <div class="offcanvas-header">
                  <div class="mx-5">
                    <img
                      class="img-logo mt-1 mx-4"
                      style="height: 170px; width: 170px; margin-top: -3.75rem"
                      src="@/assets/ujuziHubOfficialLogo.webp"
                      alt="logo"
                    />
                  </div>
                  <button
                    type="button"
                    class="btn-close text-reset mb-5"
                    data-bs-dismiss="offcanvas"
                    aria-label="Close"
                  ></button>
                </div>
                <div class="offcanvas-body">
                  <div class="dropdown mt-3">
                    <button
                      class="btn btn-secondary dropdown-toggle"
                      type="button"
                      id="dropdownMenuButton"
                      data-bs-toggle="dropdown"
                    >
                      Dropdown button
                    </button>
                    <ul
                      class="dropdown-menu"
                      aria-labelledby="dropdownMenuButton"
                    >
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li>
                        <a class="dropdown-item" href="#">Another action</a>
                      </li>
                      <li>
                        <a class="dropdown-item" href="#"
                          >Something else here</a
                        >
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  z-index: 10000000;
}
.active {
  color: #f18626 !important;
  text-decoration: underline;
}
.nav-link:hover {
  transition: 0.3s;
  padding-top: 7px;
  text-decoration: underline;
}
.bg-info {
  background-color: #3fa5c0 !important;
  color: #fff;
}
.btn-primary {
  width: 100px !important;
  height: 50px !important;
  background-color: #3fa5c0 !important;
  border: none;
}
@media (min-width: 400px) and (max-width: 650px) {
  .link-b {
    position: absolute;
    top: -10px;
    left: 19rem;
    height: 40px !important;
    width: 70px !important;
  }
  .img-logo {
    position: absolute;
    left: 0;
    top: -1.4rem;
  }
  .offcanvas {
    width: 70vw !important;
  }
}
@media (min-width: 300px) and (max-width: 398px) {
  .img-logo {
    position: absolute;
    left: 0;
    top: -1.4rem;
  }
  .link-b {
    position: absolute;
    top: -15px;
    right: 2rem;
    height: 40px !important;
    width: 70px !important;
  }
  .offcanvas {
    width: 70vw !important;
  }
}
</style>
