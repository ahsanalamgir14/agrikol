<template>
  <section class="testimonials-one">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="testimonials_one_left">
            <div class="block-title text-left">
              <p>testimonails</p>
              <h3>What our customers are<br>talking about</h3>
              <div class="leaf">
                <img src="/assets/images/resources/leaf.png" alt="">
              </div>
            </div>
            <div class="testimonials_one_text mb-4">
              <p>We're proud of the positive feedback we receive about our products and services. Our customers value
                our commitment to quality, innovation, and excellent customer service.</p>
            </div>
            <!-- <div class="project_counted wow fadeInUp" data-wow-delay="300ms">
              <div class="icon_box">
                <span class="icon-farmer"></span>
              </div>
              <di`v class="project-content">
                <h3 class="counter">1000+</h3>
                <p>Projects are completed</p>
              </di`v>
            </div> -->
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="testimonials_one_content">
            <div class="testimonials_one_carousel owl-carousel">
              <no-ssr>
                <carousel :items="1" :autoplay="true" :nav="false" :dots="true">
                  <div class="testimonials_one_single_item">
                    <div class="text">
                      <p>This is due to their excellent service, and augue homero consectetuer in nam.
                        Eu quo laoreet propriae, malis exerci habemus has vocent persius eum ea.</p>
                    </div>
                    <div class="client_thumbnail">
                      <!-- <div class="client_img">
                    <img src="/assets/images/testimonials/testimonial-1-img-1.png"
                         alt="testimonial1-img">
                  </div> -->
                      <div class="client_title">
                        <!-- <h4>Kevin Hardson</h4> -->
                        <p>Customer</p>
                      </div>
                    </div>
                  </div>
                  <div class="testimonials_one_single_item">
                    <div class="text">
                      <p>This is due to their excellent service, and augue homero consectetuer in nam.
                        Eu quo laoreet propriae, malis exerci habemus has vocent persius eum ea.</p>
                    </div>
                    <div class="client_thumbnail">
                      <!-- <div class="client_img">
                    <img src="/assets/images/testimonials/testimonial-1-img-1.png"
                         alt="testimonial1-img">
                  </div> -->
                      <div class="client_title">
                        <!-- <h4>Kevin Hardson</h4> -->
                        <p>Customer</p>
                      </div>
                    </div>
                  </div>
                  <div class="testimonials_one_single_item">
                    <div class="text">
                      <p>This is due to their excellent service, and augue homero consectetuer in nam.
                        Eu quo laoreet propriae, malis exerci habemus has vocent persius eum ea.</p>
                    </div>
                    <div class="client_thumbnail">
                      <!-- <div class="client_img">
                    <img src="/assets/images/testimonials/testimonial-1-img-1.png"
                         alt="testimonial1-img">
                  </div> -->
                      <div class="client_title">
                        <!-- <h4>Kevin Hardson</h4> -->
                        <p>Customer</p>
                      </div>
                    </div>
                  </div>
                </carousel>
              </no-ssr>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TestimonialOne"
}
</script>

<style scoped></style>
