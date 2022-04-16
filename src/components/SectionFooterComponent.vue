<template>
  <section class="p-5 bg-black-2">
    <div class="container d-flex justify-content-center align-items-center">
      <div class="row w-100 pt-5">
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold">this is dorian theme</h3>
            <p class="text-fade-1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt magni unde,
              reprehenderit quos corrupti voluptas error mollitia quae facilis commodi dolorem ipsa asperiores
              reiciendis aspernatur minima ullam possimus molestias tempora.</p>
            <div class="mb-5 mb-lg-0">
              <route-link class="text-decoration-none mx-2 text-fade-1" to="#"><i class="fab fa-instagram"></i>
              </route-link>
              <route-link class="text-decoration-none mx-2 text-fade-1" to="#"><i class="fab fa-twitter"></i>
              </route-link>
              <route-link class="text-decoration-none mx-2 text-fade-1" to="#"><i class="fab fa-facebook-f"></i>
              </route-link>
              <route-link class="text-decoration-none mx-2 text-fade-1" to="#"><i class="fab fa-pinterest"></i>
              </route-link>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold">latest post</h3>
            <div>
              <route-link
                class="text-decoration-none mb-1 d-block text-fade-1 border-bottom pb-3 mb-3 border-bottom-1px" to="#">
                <span class="text-fade-1 fw-bold">Step into the Work</span>
                <br /> April 2, 2018
              </route-link>
              <route-link
                class="text-decoration-none mb-1 d-block text-fade-1 border-bottom pb-3 mb-3 border-bottom-1px" to="#">
                <span class="text-fade-1 fw-bold">See more Do more</span>
                <br /> April 2, 2018
              </route-link>
              <route-link
                class="text-decoration-none mb-1 d-block text-fade-1 border-bottom pb-3 mb-3 border-bottom-1px" to="#">
                <span class="text-fade-1 fw-bold">Work & Design</span>
                <br /> April 2, 2018
              </route-link>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold">some widget here</h3>
            <nav>
              <route-link class="text-decoration-none mb-1 d-block text-fade-1 text-capitalize" to="#">find ot more
                about
                us</route-link>
              <route-link class="text-decoration-none mb-1 d-block text-fade-1 text-capitalize" to="#">read our awesome
                publications</route-link>
              <route-link class="text-decoration-none mb-1 d-block text-fade-1 text-capitalize" to="#">apply now and
                join the
                team</route-link>
              <route-link class="text-decoration-none mb-1 d-block text-fade-1 text-capitalize" to="#">check out our
                awarded
                projects</route-link>
              <route-link class="text-decoration-none mb-1 d-block text-fade-1 text-capitalize" to="#">drop us &
                introduce
                yourself</route-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start position-relative">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold">follow us</h3>
            <div class="row mb-3">
              <div class="col-lg-12">
                <div class="mb-1 mb-lg-3 d-flex">
                  <figure class="m-0 wh-image-50px me-0 me-lg-3">
                    <img class="img-fluid wh-image-50px o-8 me-0 me-lg-3" src="@/assets/source/image/img-1.jpg"
                      alt="image-1">
                  </figure>
                  <figure class="m-0 wh-image-50px me-0 me-lg-3">
                    <img class="img-fluid wh-image-50px o-8 me-0 me-lg-3" src="@/assets/source/image/img-2.jpg"
                      alt="image-2">
                  </figure>
                  <figure class="m-0 wh-image-50px me-0 me-lg-3">
                    <img class="img-fluid wh-image-50px o-8" src="@/assets/source/image/img-3.jpg" alt="image-3">
                  </figure>
                </div>
                <div class="d-flex">
                  <figure class="m-0 wh-image-50px me-0 me-lg-3">
                    <img class="img-fluid wh-image-50px o-8 me-0 me-lg-3" src="@/assets/source/image/img-4.jpg"
                      alt="image-4">
                  </figure>
                  <figure class="m-0 wh-image-50px me-0 me-lg-3">
                    <img class="img-fluid wh-image-50px o-8 me-0 me-lg-3" src="@/assets/source/image/img-5.jpg"
                      alt="image-5">
                  </figure>
                  <figure class="m-0 wh-image-50px me-0 me-lg-3">
                    <img class="img-fluid wh-image-50px o-8" src="@/assets/source/image/img-6.jpg" alt="image-6">
                  </figure>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionFooterComponent",
}
</script>